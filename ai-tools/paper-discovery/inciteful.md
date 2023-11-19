---
description: Find the most relevant literature, faster
---

# Inciteful

{% embed url="https://inciteful.xyz/" %}

## Introduction

The goal of Inciteful is to give the world free tools to help you map academic literature. It can be used in a variety of ways depending on what you are trying to accomplish. Start from seed paper(s), you can have an overview on the current state of that topic. Then, by adding more seed papers or filters, you can further craft the citation graph and have a focus on your search. If you are writing a paper, you can import the items in your reference list to Inciteful, and the resulting graph should be centered around the paper you are writing. Particularly, the _similar papers_ section may reveal some papers that you may have missed for inclusion via traditional keywords or citation searches.&#x20;

Unlike a traditional search engine, citations are the cornerstone of all of our tools. Building these tools for all academic literature has only recently been possible with the rise of open scholarly bibliographic data and the amazing work being done by the these groups.

### Start with a Paper

Essentially, when a paper is selected as “seed paper” in Inciteful, it will create a depth 2 graph, with the paper as node labelled 0, papers citing or cited the node 0 paper as nodes labelled 1, and secondary search for citing or cited papers of node 1 papers as nodes labelled 2. Take the following paper as an example, in total, this graph has 29,493 papers (nodes), and 300,014 citations (links). Inciteful then use algorithms to generate the most relevant papers in this graph with this underlying structure.

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/04/Inciteful-screen-cap-1.png" alt="" width="563"><figcaption><p><em>Figure 1</em>. Start with one paper as seed paper in Inciteful</p></figcaption></figure>

#### SIMILAR PAPERS

Similar papers generated from the graph are papers that cite the same papers as your selected paper. The developer chose to use [Adamic/Adar algorithm](https://help.inciteful.xyz/how-does-it-work.html#adamicadar) because it does not overly penalize a mutual paper for being popular but it still rewards papers which mutually cite less cited papers.

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/04/Inciteful-screen-cap-2-1024x737.png" alt="" width="563"><figcaption><p><em>Figure 2</em>. Similar papers of the seed paper in the citation graph</p></figcaption></figure>

#### IMPORTANT PAPERS

The “Important Papers” table is literally the place listing important or fundamental papers of a topic. [PageRank](https://help.inciteful.xyz/how-does-it-work.html#pagerank) is used as the ranking algorithm. Given the nature of academic works, PageRank algorithm tends to bias towards older highly cited papers. Nonetheless, it does give weight to papers which may not have a ton of citations but that are cited by papers which do. This is in contrast with major citation databases such as Web of Science or Scopus, whose result lists, if sorted by “times cited”, are only based on the number of the citations each item gained of all times.

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/04/Inciteful-screen-cap-3-1024x664.png" alt="" width="563"><figcaption><p><em>Figure 3.</em> Most important papers in the citation graph</p></figcaption></figure>

### Customize Your Own Citation Graph

If there is only one seed paper, the citation graph will have a depth of two by default. The slick thing about inciteful is that if there are multiple seed papers, then node labelled 0 becomes a fake, non-exist paper that cites those seeds papers (node 1), and node 2 are all papers which are cited by or cite the seed papers. Because of this fake node 0, you can craft a graph specific to the topic of your interest and therefore understand the underlying structure of the graphs which is created just for you.

Adding seed papers and/or applying filters is an iterative process for achieving a graph with better precision. I find this process delightful and inspirational as I see the lists becoming more and more relevant every time I refine my selection of seed papers.

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/04/Inciteful-screen-cap-4-1024x281.png" alt="" width="563"><figcaption><p><em>Figure 4.</em> Five papers selected as seed papers in the graph</p></figcaption></figure>

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/04/Inciteful-screen-cap-5-1024x707.png" alt="" width="563"><figcaption><p><em>Figure 5</em>. The new similar papers list after adding more seed papers</p></figcaption></figure>

Finally, the _other data_ section shows who are publishing the papers, their affiliations, as well as the publication venues. This is useful for us to see who the field experts are, and potential journals where we can submit the manuscript to.

{% embed url="https://www.youtube.com/watch?v=94bJm52XLZM" %}

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
