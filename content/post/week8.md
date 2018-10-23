+++
title = "Week 8: 'Fun with Data' Hands-on"

date = 2018-10-22T00:00:00
lastmod = 2018-10-22T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Bodong Chen"]

tags = ["Tools", "Data"]
summary = "Consider the data pipeline and play with data wrangling tools."

[header]
image = "https://images.pexels.com/photos/1251179/pexels-photo-1251179.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
caption = "Image credit: [**pixabay**](https://www.pexels.com/photo/person-flattening-dough-with-rolling-pin-1251179/)"
+++

**Data wrangling**, or data munging, is a critical part of any learning analytics project. It covers multiple components of the *Learning Analytics Model* including the collection, storage, cleaning, and integration of data (see Siemens 2013, which we read in [Week 1](https://colig.github.io/laumn/post/week1/)).

![LA Model by Siemens](https://c1.staticflickr.com/3/2814/9662456144_51b12d6057_b.jpg)

Due to the quantity of data and the diversity of data sources, a learning analytics project often necessicitates data wrangling -- conducted by humans -- in order to transform data into actionable intelligence and systematic action ([Clow, 2012](https://dl.acm.org/citation.cfm?doid=2567574.2567603)). 

This week, we will:

1. Familiarzie with the concept of data wrangling
2. Play with at least one data-wrangling tool of your choice
3. Share your data-wranglinge experiences with peers
4. Draft a data-wrangling plan with your Working Group members

## What is data wrangling?

According to [Wikipedia](https://en.wikipedia.org/wiki/Data_wrangling):

> **Data wrangling**, sometimes referred to as data munging, is the process of transforming and mapping data from one "raw" data form into another format with the intent of making it more appropriate and valuable for a variety of downstream purposes such as analytics. A **data wrangler** is a person who performs these transformation operations.

Over the past years, I have seen polls of data scientists (like [this one](https://www.forbes.com/sites/gilpress/2016/03/23/data-preparation-most-time-consuming-least-enjoyable-data-science-task-survey-says/#4d660d346f63)) showing they spend 60% of their time 'massaging' instead of analyzing data. This percentage may even go up to 80-90% [in some reports](https://www.infoworld.com/article/3228245/data-science/the-80-20-data-science-dilemma.html).

<!-- ![](https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fblogs-images.forbes.com%2Fgilpress%2Ffiles%2F2016%2F03%2FTime-1200x511.jpg) -->

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">“90% of data science is wrangling data, the other 10% is complaining about wrangling data.”<a href="https://twitter.com/evelgab?ref_src=twsrc%5Etfw">@evelgab</a> at <a href="https://twitter.com/hashtag/rstatsnyc?src=hash&amp;ref_src=twsrc%5Etfw">#rstatsnyc</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/987436677026254848?ref_src=twsrc%5Etfw">April 20, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<!-- ![](https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fblogs-images.forbes.com%2Fgilpress%2Ffiles%2F2016%2F03%2FLeast-Enjoyable4-1200x511.jpg) -->


## Plan and Resources This Week

As each Working Group project starts to take shape, this week provides each group an opportunity to **consider the data aspect** and **draft a Data Wrangling plan** for the project. 

Below are activities designed for this week.

### 1. Watch a lecture on data wrangling 

This lecture was delivered by [**Tony Hirst**](https://blog.ouseful.info/about/) to the [*Data, Analytics and Learning* MOOC](https://www.edx.org/course/data-analytics-learning-utarlingtonx-link5-10x) in 2014. Tony is an active blogger, and [his blog](https://blog.ouseful.info/) has always been a great source of inspiration for me. 

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/wszwwbWftUs" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 2. Play with one data wranging tool of your choice

Our choices include -- but are not limited to -- the following:

**Spreadsheets**. Yes, spreadsheets (e.g. Excel, Google Sheets) are incredibly powerful when it comes to data wrangling. Below are two tutorials that may help you unleash the power of spreadsheets.

- [School of Data: A Gentle Introduction to Data Cleaning](https://schoolofdata.org/courses/#IntroDataCleaning)
- [Data Carpentry: Data Organization in Spreadsheets](http://www.datacarpentry.org/spreadsheet-ecology-lesson/)
<!-- - [School of Data Handbook: Using a spreadsheet to clean up a dataset](https://datapatterns.readthedocs.org/en/latest/recipes/cleaning-data-with-spreadsheets.html) -->

**OpenRefine**, formerly Google Refine, "is a powerful tool for working with messy data: cleaning it; transforming it from one format into another; and extending it with web services and external data." [Its official website](http://openrefine.org/) provides several introductory videos to get you started. There is [a Data Capentry course on OpenRefine for Social Science Data](https://datacarpentry.org/openrefine-socialsci/). 

**Dataiku Data Science Studio ([DSS](https://www.dataiku.com/dss/index.html))**. A data science workbench that provides a Graphical User Interface (GUI) similar to OpenRefine. I've recorded a tutorial video (of an earlier version) to demonstrate its usefulness for data wrangling. [More tutorials](https://www.dataiku.com/learn/guide/tutorials/basics.html) can be found on its official website.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/uNYrjeoPFGU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

**R and RStudio**. If you know R basics, I strongly encourage you to spend some time on the `tidyverse` ecosystem. It has absolutely transformed my data wrangling practices in R. 

- [RStudio webinar on data wrangling](https://www.rstudio.com/resources/webinars/data-wrangling-with-r-and-rstudio/)
- [Lynda.com course on Data wrangling with R and RStudio](https://www.lynda.com/R-tutorials/Data-Wrangling-R/594442-2.html)

**Python**, another popular programming language among data scientists. There are plenty of tutorioals out there. Below are just two examples. 

- [Wrangling data with `Pandas`](https://towardsdatascience.com/wrangling-data-with-pandas-27ef828aff01)
- [Wrangle Data in Jupyter Notebooks with `PixieDust Rosie`](https://medium.com/ibm-watson-data-lab/wrangle-data-in-jupyter-notebooks-with-pixiedust-rosie-7d9ac1129925)

This list is by no means exhaustive or comprehensive. **Is there a data wrangling tool you like? Let us know by leaving a Hypothesis annotation here!**

### 3. Share your journey as a Data Wrangler via Slack

![](https://upload.wikimedia.org/wikipedia/en/thumb/f/ff/SuccessKid.jpg/256px-SuccessKid.jpg)

Yes, we can do it!  How did your journey go? Have you discovered your data-wrangling superpower? Share a blurb about your journey in the `#general` channel of Slack. 

For Open Participants, please tweet under the `#LAUMN` hashtag.

### 4. Discuss a data-wrangling plan with your Working Group

What implications does this week's work have on your Working Group project? Discuss with your group members anywhere you like (e.g. Slack, Zoom, F2F). 

## Housekeeping for Formal Participation

**There will be _no_ Zoom meeting on Oct 29** to provide us more 'play time'. 

**The first SIG Session on *Social Networks* will happen on Nov 5.** Details will be posted on Oct 29.

Enjoy digging!

![](http://gif-finder.com/wp-content/uploads/2016/06/Dog-Digging.gif)