+++
title = "Week 9: Social Networks (SIG 1)"

date = 2018-10-28T00:00:00
lastmod = 2019-10-29T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
#authors = ["Crystal Rose-Wainstock", "Nicholas Spase", "Rukmini Manasa Avadhanam", "Angelina Constantine"]

tags = ["Tools", "Data"]
summary = "SIG 1 on Social Network Analysis."

[header]
image = "https://images.unsplash.com/photo-1456428746267-a1756408f782?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=2696ce6a989356246b5b2522227c2182&auto=format&fit=crop&w=1650&q=80"
caption = "Image credit: [**pixabay**](https://www.pexels.com/photo/person-flattening-dough-with-rolling-pin-1251179/)"
+++

This week, we will be diving into Social Network Analysis as an approach to studying the exchange of information. Social network analysis looks at various patterns of relationships between different actors and examines the availability and exchange of resources between them (Scott, 1991; Wasserman & Faust, 1994). The actors exchanging resources and information could be individuals or organizations and their relationships determine the kind of information exchanged. 

Here is a short video to help you through the definition of social network analysis better. 

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/xT3EpF2EsbQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<!-- ![](https://cdn-images-1.medium.com/max/1600/1*2rOTpI5RyI8V-mMRfCv_fw.png) -->

## Plan and Resources this Week:

### 1. Read & annotate 

- [Grunspan et al. (2017)](https://www.lifescied.org/doi/10.1187/cbe.13-08-0162). A primer that introduces how an SNA research project can be done in education. 
- [Chen et al. (2018)](/laumn/files/chen-et-al-2018.pdf). A case study of building an analytic tool based on SNA for student sense-making.

Consider the following questions as you read the articles about SNA: 

- What are the key elements of an SNA project based on the Grunspan et al. (2017) article?
- What tools do you notice the authors using for SNA?
- What considerations are needed when applying SNA in teaching practice?
- How do you see SNA being of use to your WG project?

As we continue to work on WG projects, please keep in mind your group tags when annotating. By doing so, we will be able to index our ideas as we continue to engage with all sorts of resources. 


### 2. Explore social network analysis tools

#### Gephi

**[Gephi](https://en.wikipedia.org/wiki/Gephi)** is an open-source network analysis tool based on Java. To explore Gephi, check out one or more of the following resources:

- [Gephi.org](https://gephi.org/)
- Overview of Gephi
    - [Gephi: Making your relational data very pretty](https://www.youtube.com/watch?v=2FqM4gKeNO4) -- This tutorial is kind of long, but it uses sample data to explore many of the features of Gephi.
    - [The Complete n00b’s Guide to Gephi](http://www.briansarnacki.com/gephi-tutorial/) -- This article breaks down how to start using Gephi. It’s a nice simple resource to get started.

Download Gephi (from gephi.org) and explore the features it has. The download comes with sample data using characters from *Les Miserables*. The video tutorial linked above uses that data to demonstrate many of the features of Gephi. If you’re unable to use Gephi on your personal computer, you might consider connecting with a classmate who is able to use it successfully. *Note*: You may need to download/update Java on your computer.

If you have any issues or questions as you’re exploring this tool, please reach out to your colleagues on Slack.

#### R or Python

If **R** is your go-to "Swiss Army knife" for data analysis, check out one of the packages such as **[`igraph`](https://igraph.org/r/)**, **`sna`**, and **[`statanet`](http://www.statnet.org/)**. 

If you prefer **Python**, check out **[`networkx`](https://networkx.github.io/)** or **[`igraph`](https://igraph.org/python/)**. 

#### Other network analysis tools

Some of you have taken my SNA class (CI 8371) and please consider exploring other novel network analysis tools. 

- Using Gephi, you can [analyze dynamic networks](https://seinecle.github.io/gephi-tutorials/generated-html/converting-a-network-with-dates-into-dynamic.html).
- [Epistemic Network Analysis](http://www.epistemicnetwork.org/) (ENA) is a method for identifying and quantifying connections among elements in coded data and representing them in dynamic network models. A key feature of the ENA tool is that it enables researchers compare different networks, both visually and through summary statistics that reflect the weighted structure of connections.
- [Exponential random graph models (ERGMs)](https://github.com/statnet/ergm) is a family of statistical models for analyzing networks . See [tutorial](https://statnet.org/trac/raw-attachment/wiki/Sunbelt2016/ergm_tutorial.html).
- `statnet` provides a suite of packages for analyzing temporal networks. See [tutorial](http://statnet.csde.washington.edu/workshops/SUNBELT/current/ndtv/ndtv_workshop.html).

![](https://i.giphy.com/media/l2YWSmwWULoAw/giphy.webp)

### 3. Use data from Hypothes.is annotations to make a visualization

#### 3.1. Data wrangling challenge

First, use the [Hypothesis data exporting tool](https://jonudell.info/h/facet/) to extract some sample data from our group. Please choose the CSV format as it is the most helpful format for this activity.

Transform the exported data to a format that works for Gephi or a tool of your choice. Consult with the first reading and Gephi tutorials for information about acceptable formats. 

Please feel free to share your cleaned data on Slack and to help each other.

#### 3.2. Network analysis challenge

Import the data into Gephi (or a tool of your choice) and create a visualization of our interactions. 

You can also play with other functions such as computing centrality measures and detecting communities in our group. 

Be prepared to share your adventures during our Zoom meeting on **Monday, November 4th**!

![](https://i.giphy.com/media/l0IylOPCNkiqOgMyA/giphy.webp)
