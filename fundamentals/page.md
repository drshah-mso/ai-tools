# Page

### The Effortless Literature Review

Literature review does not need to be time consuming or confusing. Effortlessly find literature, use AI to screen for relevance and "3-step-filtering" to find the top 10% papers in your collection.

Let’s look at the steps:

<figure><img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0d992c96-21a0-44e5-9f0e-ff87b85e8d88_2954x3369.jpeg" alt="" width="563"><figcaption></figcaption></figure>

This seems like many steps - but you probably know some of them already. The effortlessness comes from integrating them with one another and leveraging the synergy between them.

### 1. Finding “Seeds”

{% content-ref url="../ai-tools/lit-search/google-scholar.md" %}
[google-scholar.md](../ai-tools/lit-search/google-scholar.md)
{% endcontent-ref %}

The old ways of finding papers is to “google” them, e.g. on Google Scholar or Arxiv.

If you search for “yeast” you may find papers on:

* Brewing science (yeast as a fermentation agent)
* Molecular biology (yeast as a model organism)
* Medical science (yeast as infection)
* Evolution (yeast by itself)

<figure><img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb9b1097c-bb36-4c12-9906-1b48ec051e1f_2954x2037.jpeg" alt="" width="563"><figcaption></figcaption></figure>

Google would usually rank higher cited papers at the top. Molecular biology and medicine are huge domains. So effectively you will find much less on evolution.

**Problem:** Finding all relevant literature in such cross-domain fields becomes challenging. Separating important from irrelevant is even harder.

Scite.ai (20$/mo) can help here by hinting at the _**importance**_ of individual papers. It can tell you how often a paper has been supported or contrasted.

{% content-ref url="../ai-tools/lit-search/scite-ai.md" %}
[scite-ai.md](../ai-tools/lit-search/scite-ai.md)
{% endcontent-ref %}

Papers with supporting claims are not “just mentioned” but actually validated. So the connection in our publication network is stronger and thus indicated relevance.

Luckily you can use both - as scite integrates into google scholar.

<figure><img src="https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F7fd548e0-960f-4ddd-9aef-557f0f4abc1a_2536x909.jpeg" alt="" width="563"><figcaption></figcaption></figure>

[Scite.ai](https://scite.ai/) will also allow us to find where and how exactly a paper is mentioned (i.e. let us see the mentioning snippet). It is an amazing tool that integrates well with the rest of the academic tool eco system.

This combination of google scholar and scite.ai is a great way to find the first few papers. Their citations and references will give us access to all the other relevant papers (Step 3).

### 2. Analyze abstracts with AI

{% content-ref url="../ai-tools/chatbot/chatgpt/arxivgpt.md" %}
[arxivgpt.md](../ai-tools/chatbot/chatgpt/arxivgpt.md)
{% endcontent-ref %}

ArxivGPT is a Google Chrome extension that helps you quickly understand the content of arXiv papers. It uses a large language model, also known as a conversational AI or chatbot trained to be informative and comprehensive. ArxivGPT is trained on a massive dataset of arXiv papers, and it can summarize the content of a paper in a few sentences, highlighting the key ideas and concepts.

To use ArxivGPT, simply install the extension and open an arXiv paper in your browser. The extension will automatically detect the paper and generate a summary. You can also click on the extension icon to manually generate a summary.

ArxivGPT is a useful tool for researchers, students, and anyone who wants to stay informed about the latest developments in their field. It can save you time and help you quickly grasp the main ideas of a paper.

With a little bit of creativity you can use ArxivGPT not to summarize abstracts but to ask it to RATE them.

People are weary of using ChatGPT in science, because it creates fake citations, doesn’t know math and is [over confident](https://www.reddit.com/r/ChatGPT/comments/10jshk5/why\_is\_chat\_gpt\_confident\_in\_every\_answer/).

{% content-ref url="../ai-tools/chatbot/chatgpt/" %}
[chatgpt](../ai-tools/chatbot/chatgpt/)
{% endcontent-ref %}

But ChatGPT is good at one thing: Comparing text.

If you design your prompts to describe what you are looking for and then add the abstract of a paper the results will surprise you.

In this example I used a simple prompt and asked it to rate for relevance. And indeed the results are spot-on!

<figure><img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F16cb53e2-71a4-4444-8f47-d2e2281dc2d5_2536x1348.jpeg" alt="" width="563"><figcaption></figcaption></figure>

This allows me to screen papers for relevance. You can ask ANY question that could be answered from the abstract and without domain knowledge.

There are so many way this workflow can be used:

* Filter method papers, from theory papers
* Identify papers working with a specific model organism, algorithm or methodology
* Identify what the authors themselves see as potential limitations (discussion)
* Summarize in different formats (keywords, bullets, sentences)

### 3. Growing your collection

Once you have acquired a few seed papers, it is time to start exploring the citation network. Go through the list of _**references**_ at the end of your seed paper and you will find all the papers _**in the past**_.

The problem here is that you can only go back in time - not forward.

<figure><img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F5952b9a4-46ad-41ba-bedd-43f8094d6c60_2432x1574.jpeg" alt="" width="563"><figcaption></figcaption></figure>

References are easy to find, but they only look into the past. We need _**citations**_ to find out how the field has developed since.

In the past you would look into the _**journal**_ of the publication and read a more recent issue. But citations can be scattered across many journals.

Today the journal method is outdated. There are tools to find everything much more easily and visually.

My all-time favourite tool for the job is [Litmaps](https://litmaps.com/). In [Gourmet Literature Review](https://ilyashabanov.substack.com/p/gourmet-literature-review) I described how we can use it, so I won’t go into too much detail here. But to give you an overview, this is how it looks:

<figure><img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Faa192169-f81f-4d67-a1e5-5b96b3fc5b36_2533x2300.jpeg" alt="" width="563"><figcaption></figcaption></figure>

{% content-ref url="../ai-tools/paper-discovery/litmaps.md" %}
[litmaps.md](../ai-tools/paper-discovery/litmaps.md)
{% endcontent-ref %}

**Seed maps** in Litmaps show us all publications related (references and citations) to a _**single**_ publication. They are an effortless way of discovery where we don’t have to drill through references lists.

**Discovery** in Litmaps shows us similar papers to a collection of papers we already have.

So each time we look at either of these we can add new papers and grow our collection.

Litmaps will be at the very core of the Effortless Literature Review Workshop (March 18th or as a download after).

**Bonus: I invited the CEO of Litmaps and you can ask him anything you want about the tool or even make suggestions!**

[More Info on the Workshop](https://effortlesslitreview.carrd.co/)

### 4. Importance Filtering

After you have grown your collection in the previous step you will probably end up with 100s of papers. Impossible to read.

My method is to filter in 3 steps or cuts. Identify the:

* 10% most recent
* 10% most cited
* 10% reviews

Archive the rest of the papers for later (or never).

All of this is easy to do with Litmaps and Zotero. Luckily those two work together through an exchange format called BibTeX. I can import and export papers from one to another.

This workflow is also partially described in the [literature review article](https://ilyashabanov.substack.com/p/gourmet-literature-review). Since writing the article I added scite.ai to also look and sort for _**controversial**_ papers.



In the picture above you see that the Mori 2018 paper did receive the least citations of the 5. But it has more debate going on as there are many supporting claims as well as someone contrasting it.

This paper is therefore _**debated**_. (And indeed it is, this paper is about the link of biodiversity to ecological functions or eco system services. First of all we don’t know for sure where biodiversity comes from and second we only start to understand what services eco systems provide (i.e. air/water purification, climate regulation, flood protection) etc. Of course it is a subject of scrutiny! )

This integration allows us to identify _**ongoing debates**_ in the field. And this is where “science” happens. You can quickly learn arguments around your field with precisely these papers.

I will show you many other examples in the webinar - join us, it is just 15$ as last time or a recording if you can’t attend.

[Boost your Literature Review with AI](https://effortlesslitreview.carrd.co/)

### 5. Reading and taking notes

Note taking is actually the more important skill when doing research. In my last article I wrote about [boosting creativity](https://ilyashabanov.substack.com/p/creativity-on-autopilot) and generating ideas on auto-pilot by using the right tools and methods.

**Problem**: We summarize what we read but we focus less on connecting them.

That is because our brain is a connecting system. So even by summarizing we get new ideas through the subconscious workings of the mind.

But our mind has limits. That means the number of ideas generally won’t scale indefinitely with the amount of information we consume. At some point you will start forgetting and this replaces older knowledge.

The right note taking system can help here. We can let our tools generate some of the connections we miss with our mind. Plus everything is stored forever.



This graph visualizes the idea.

In gray are notes that summarize what I know (here: on proteins A,B,C,D…). While some of them are connected because I _**thought**_ of it, others are connected in two steps by the green and purple nodes. These are tags and maps of content respectively.

By tagging two notes with the same label I connect them, but without explicitly thinking of it.

This is the “auto-pilot” aspect of this method. We only think of tagging N notes. The number of possible connections between them is N \* (N - 1). For 100 notes this is 9900 connections - impossible to think of manually.

In the [upcoming workshop](https://effortlesslitreview.carrd.co/) we will talk about this as well as the idea of [visual reference management](https://ilyashabanov.substack.com/p/from-reference-manager-to-reference) (VRM).

If you have used Zotero or another reference manager you have encountered these endless lists of papers with the only way to navigate being the search bar.

But you can only search for what you can recall i.e. title, author or tag of a paper you saved.

VRM allows you to lay out the papers _**visually**_ on a canvas and connect them in groups or individually.



The result is that you can now use your _**spatial memory**_ to remember your publications. Humans have evolved from animals that had to roam vast landscapes in search for food, naturally our spatial memory is quite well developed.

Concepts on the other hand are abstract and only a very recent evolutionary development. That’s why you can remember the neighbourhood of your childhood even decades later.

We will develop a visual reference manager in Obsidian in the Effortless Literature Review workshop. Join if you like the idea.

[Learn Visual Reference Management](https://effortlesslitreview.carrd.co/)

### Summary

Literature Review is central to any researcher and also the most time consuming part of science.

Tools and polished workflows can cut the time you spend on it. They can help you create an overview, identify debates and “hot topics”.

Just 5 years ago most of the tools I am using here did not exist. If you have been in research that long, chances are you might have missed out on some of them.

This is why I created the Effortless Literature Review workshop. It will get you up to date and hopefully boost your career in the long run.

Those tools are not complicated. They are increasingly more customer focused and user experience based. That is why I am very confident that you can learn most of it in just about 2 hours.

I hope to see you in this workshop (March 18th, \~noon in the US, \~evening in the EU). I priced it at 15$ dollars to keep it accessible to everyone. Reach out to me with questions you have.

[Effortless Literature Review Workshop](https://effortlesslitreview.carrd.co/)

[![](https://substackcdn.com/image/fetch/w\_80,c\_limit,f\_auto,q\_auto:good,fl\_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F8106078d-a956-4fae-84ba-f3de783f6e99\_144x144.png)](https://substack.com/profile/108806636-yn?utm\_source=post-reactions-face)[![](https://substackcdn.com/image/fetch/w\_80,c\_limit,f\_auto,q\_auto:good,fl\_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4ed15836-25a9-49b5-b812-1617d21fab01\_144x144.png)](https://substack.com/profile/32694778-bahati-samson?utm\_source=post-reactions-face)[![](https://substackcdn.com/image/fetch/w\_80,c\_limit,f\_auto,q\_auto:good,fl\_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F01daf9c1-fe30-47e2-a80f-b8bebe9594bc\_144x144.png)](https://substack.com/profile/133177079-asrul?utm\_source=post-reactions-face)[![](https://substackcdn.com/image/fetch/w\_80,c\_limit,f\_auto,q\_auto:good,fl\_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F7ea5dfd5-734a-476c-9eba-066e0bb82db4\_1125x1125.jpeg)](https://substack.com/profile/131371624-maite-goya-arce?utm\_source=post-reactions-face)[![](https://substackcdn.com/image/fetch/w\_80,c\_limit,f\_auto,q\_auto:good,fl\_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F19295b06-3d26-4809-9caa-c79b104af504\_144x144.png)](https://substack.com/profile/54889239-cc-hh?utm\_source=post-reactions-face)13 Likes13ShareComments![](https://substackcdn.com/image/fetch/w\_64,h\_64,c\_fill,f\_auto,q\_auto:good,fl\_progressive:steep/https%3A%2F%2Fsubstack.com%2Fimg%2Favatars%2Flogged-out.png)TopNewCommunity[Note Taking System For Success in Academia](https://ilyashabanov.substack.com/p/note-taking-system-for-success-in)[Say Goodbye to Microsoft Word and writer's block. Welcome Obsidian and the SCTO methodology to gather and store your knowledge. Build understanding and…](https://ilyashabanov.substack.com/p/note-taking-system-for-success-in)DEC 14, 2022 • [ILYA SHABANOV](https://substack.com/@ilyashabanov)![](https://substackcdn.com/image/fetch/w\_320,h\_213,c\_fill,f\_auto,q\_auto:good,fl\_progressive:steep,g\_center/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Faee4dbaf-b466-412c-b3ce-75383d56266e\_1306x907.jpeg)30[8](https://ilyashabanov.substack.com/p/note-taking-system-for-success-in/comments)[Adding AI to your Academic Workflow](https://ilyashabanov.substack.com/p/adding-ai-to-your-academic-workflow)[ChatGPT has taken the world by storm, but it has issues. Let's learn how it works to avoid them and integrate it with our notes for the AI ready…](https://ilyashabanov.substack.com/p/adding-ai-to-your-academic-workflow)APR 7 • [ILYA SHABANOV](https://substack.com/@ilyashabanov)![](https://substackcdn.com/image/fetch/w\_320,h\_213,c\_fill,f\_auto,q\_auto:good,fl\_progressive:steep,g\_center/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fece4e11e-34f1-47f1-9131-9bfc6d2deae0\_1280x947.jpeg)10[1](https://ilyashabanov.substack.com/p/adding-ai-to-your-academic-workflow/comments)[5 Indispensable AI Tools for Academics](https://ilyashabanov.substack.com/p/5-indispensable-ai-tools-for-academics)[AI has exploded this year and its hard to keep up with 1000s of projects going on. In this newsletter we are going to look at the top tested tools for…](https://ilyashabanov.substack.com/p/5-indispensable-ai-tools-for-academics)MAY&#x20;
