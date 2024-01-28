# Connected Papers

{% embed url="https://www.connectedpapers.com/" %}

Connected Papers works by analyzing the citations between research papers. This allows it to create a network of papers that are connected to each other. The network can be used to explore the connections between different papers, identify gaps in the literature, and find new research opportunities. Connected Papers is a valuable tool for researchers, students, and anyone who is interested in learning more about the latest research.

Connected Papers lists the following [operations](https://www.connectedpapers.com/about) \[1] on its website.

* **To create each graph, Connected Papers analyzes an order of \~50,000 papers** and selects a few dozen with the strongest connections to the origin paper.
* In the graph, **papers are arranged according to their similarity**. That means that even papers that do not directly cite each other can be strongly connected and very closely positioned. **Connected Papers is not a citation tree**.
* Their similarity metric is based on the concepts of **Co-citation and Bibliographic Coupling**. According to this measure, two papers that have highly overlapping citations and references are presumed to have a higher chance of treating a related subject matter.
* Their algorithm builds a **Force Directed Graph** to distribute the papers in a way that visually clusters similar papers together and pushes less similar papers away from each other. Upon node selection, they **highlight the shortest path from each node to the origin paper** in similarity space.
* Their database is connected to the [Semantic Scholar Paper Corpus](https://www.semanticscholar.org/paper/Construction-of-the-Literature-Graph-in-Semantic-Ammar-Groeneveld/649def34f8be52c8b66281af98ae884c09aef38b) (licensed under ODC-BY). The team has done the job of compiling **hundreds of millions of published papers across many scientific fields**.

#### STARTING A GRAPH WITH ONE PAPER

To start your exploration using _Connected Papers_, you need a “seed paper”. Simply put the **doi** (Digital Object Identifier, a type of Persistent ID) of your seed at the front page:

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/02/connected-papers-entrypage-1-1024x645.png" alt="" width="563"><figcaption></figcaption></figure>

This example is a[ 2012 article](http://repository.ust.hk/ir/Record/1783.1-57039) by [Prof. Dalton (MARK)](http://repository.ust.hk/ir/AuthorProfile/dalton-amy-n). _Connected Papers_ built a graph that consisted of 40 similar papers. Only 5 papers in the graph were cited by the seed paper.

In the graph shown below. You can see the original paper marked. Each node is a related paper; **node size** is the number of citations. **Color** is the publication year; the **lines and proximity** represent similarity. You can explore the graph, paying attention to the visual elements such as:

* bigger nodes that represent highly-cited papers, e.g. “Gollwitzer, 2006”
* darker nodes, which are more recent works
* clusters of nodes that are close together, meaning that they are similar
* “outliners”, such as “Townsend, 2011” or “Bayuk, 2010”, which might carry an approach to the topic different from the rest of the group

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/02/connected-papers-graph-1.png" alt="" width="563"><figcaption></figcaption></figure>

#### SHOW DETAILS OF OTHER PAPERS

You can mouse over any node; the details of the corresponding paper is shown on the right panel. For example, this screen shot shows the information about “Gollwitzer, 2006”; you can build a new graph using it as a new seed:

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/02/connected-papers-detail-1024x532.png" alt="" width="563"><figcaption></figcaption></figure>

#### LINKING BACKWARD AND FORWARD IN TIME

Co-citation is one of the concepts that _Connected Papers_ uses to calculate similarity. The two buttons at the top-left of the screen are useful to find older and later articles that have common citation relation with the papers in the graph.

<figure><img src="http://library.hkust.edu.hk/sc/wp-content/uploads/sites/5/2021/02/connected-papers-prior-300x197.png" alt="" width="375"><figcaption></figcaption></figure>

In this example, the “**Prior works**” set contains 10 papers, published from 1993 to 2007, that were most commonly cited by the papers in the graph. These are probably important works in the field. Using a similar idea, the **“Derivative works**” set contains 10 papers, published from 2010 to 2018, that cited many of the papers in the graph. These may be survey of the field (i.e. literature review), or recent works which were inspired by many papers in the graph.

#### EXPORTING THE LISTS

Apart from the Graph view, you can “Expand” to see the papers listed with more details. On the detail screen, you can use the “download” button to save the list of bibliography. There are options to directly import into citation managing software such as Zotero.

{% embed url="https://youtu.be/efQmSW24UKE" %}

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
