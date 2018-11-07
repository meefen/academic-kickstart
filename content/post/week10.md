+++
title = "Predictive Modeling"

date = 2018-10-28T00:00:00
lastmod = 2018-10-29T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Neal Fredrickson & Matt Vernon"]

tags = ["Tools", "Data"]
summary = "SIG 2 on Predictive modeling and predictive analytics."

[header]
image = "https://upload.wikimedia.org/wikipedia/en/0/07/Self_oraganizing_map_cartography.jpg"
caption = "Image credit: [**Wikipedia**](By Denoir - Using my own software, CC BY-SA 3.0, https://en.wikipedia.org/w/index.php?curid=40452073)"
+++

# "All models are wrong; some are useful"

By the end of this week we hope that you will be able to better understand and explain this quote. This week, we will be surveying predictive modeling in education using a combination of readings and tools to work with data. **Let's get started!**


## Plan and Resources for this Week:

### 1. Take this [quick survey](https://docs.google.com/forms/d/e/1FAIpQLScIsWz2HdqM81N46mfZVMHjWeNmZY_rhfHGSdeeUw8FriUx_Q/viewform?usp=sf_link)

<!-- Annotate as usual with “good points, useful points, muddy points.” We won’t be using FROG this week, but you can use these tags to keep track of points relevant for your WG. -->

### 2. Readings

1. **Required**: Brooks and Thompson. Handbook of Learning Technologies Chp 5. [“ Predictive Modelling in Teaching and Learning"](https://solaresearch.org/wp-content/uploads/2017/05/chapter5.pdf)
2. **Choose one additional reading**:
  - Manuel Ekowo and Iris Palmer, Oct 2016. ["The promise and peril of predictive analytics in higher education"](https://na-production.s3.amazonaws.com/documents/Promise-and-Peril_4.pdf)
  - Steven Tang, Joshua C. Peterson & Zachary A. Pardos, 2017.["Predictive Modeling of Student Behavior Using Granular Large-Scale Action Data"](https://solaresearch.org/hla-17/hla17-chapter19/)

Annotate as usual with “good points, useful points, muddy points.” We won’t be using FROG this week, but you can use these tags to keep track of points relevant for your WG.

### 3. Consider the following questions as you read the articles about Predictive Modeling: 

- How is predictive modeling different than explanatory modeling? 
- What common issues are confronted in collecting data? How can that influence feature selection and algorithm choice in the model?
- What is involved in testing and evaluating a model, why can't it be ignored in the process?
- What would be an example of second order predictive modeling that you would be interested in?


#### Optional Video Extras

These might be helpful to you, they were to me!

- 2min video [“6 steps of predictive modeling with machine learning"](https://www.youtube.com/watch?v=J2xSIIK2OzQ)
- CrashCourse ["Correlation≠Causation"](https://www.youtube.com/watch?v=GtV-VYdNt_g)

---

## Play Time

### 4. Model building tools and data sets.

Weka is described as a ["machine learning workbench"](https://machinelearningmastery.com/what-is-the-weka-machine-learning-workbench/) it has a straightforward GUI and is open source. This tool runs on PC, Mac & Linux. I am running on a Mac but does require java, so if you run into install issues that's most likely the culprit. Reach out on slack if you do.

- Step 1 Download and install [Weka](https://www.cs.waikato.ac.nz/ml/weka/downloading.html)
- Step 2 Watch [this video](https://tinyurl.com/y77y7ltj) and follow along on how to load data sets, select features, classify, compare results, evaluate and test a model.
- Optional Challenge Activity! Format and create a model for your own data set [Use this blog post](https://edumine.wordpress.com/2014/08/23/fix-arff-file-not-recognised-or-unable-to-load-data-in-weka/) to learn how to create a WEKA formatted file to use with the program. Rank the features sets to determine which attributes are useful.

### 5. Prep for Zoom meeting. Guided Practice.

Neal has created an analysis tool in google sheets and supplied it with data. Your task is two identify two models using the tool and data to share with your small group.

- Step 1 [Make a copy](https://docs.google.com/spreadsheets/d/1i4bjFMnjLH21-Dv9-g0rZJflvaglQ5LmjIcWzBpIcho/copy) of the spreadsheet in google docs.
- Step 2 [Watch Neal](https://www.youtube.com/embed/OVsKev9NtVs) take you through the steps of making predictions using the tool.

  >This is survey data retrieved from students in CI5301 “Foundations of Computer Applications for Business and Education.” 
  >Students responded to questions at the beginning and at the end of the semester to measure their change in digital literacies (website building skills, information management,  
  >screencasting, etc...) 

#### More Context about the Data
Students answered the following questions on a 1-5 Likert-type scale. 1 = very low skill, 5 = very high skill. The data presented here is the difference between their self ratings at the end of the semester and their self ratings at the beginning of the semester. That is, these numbers represent their “growth” or “change” in ratings over the course of the semester.

**Predictor Variables (Independent Variables)**

- **dWebDes:** “How proficient are you with Web Design for professional purposes?”
- **dSiteMap:** “How proficient are you with Concept / Site Mapping for professional purposes?”
- **dScreencast:** “How proficient are you with Screencasting for professional purposes?”
- **dVideoHost:** “How proficient are you with Video Hosting for professional purposes?”
- **dVideoConference:** “How proficient are you with Video Conferencing for professional
purposes?”
- **dInfoMgt:** “How proficient are you with Information Management for professional purposes?”
- **dProjectMgt:** “How proficient are you with Project Management for professional
purposes?”
- **dCollaboration:** “How proficient are you with Collaboration Tools for professional
Purposes?”
- **dGraphDes:** “I know how to apply graphic design concepts to creating aesthetically-pleasing digital media products.”
- **dSelfLearn:** “I know how to learn a new computer program on my own using instructional videos and resources on the web.”
- **dProblemSolve:** “I know how to apply appropriate technological solutions to real-world problems.”
- **Female:** 1 = female; 0 = male.
- **Athlete:** 1 = student athlete; 0 = not student athlete

**OutcomeVariables** (Dependent Variables)

- **ParticipationGrade:** Student grade for first major project out of 100 possible points
- **Project1Grade:** Student grade for pitch major project out of 100 possible points
- **Project2Grade:** Student grade for website major project out of 100 possible points
- **Project3Grade:** Student grade for webinar major project out of 100 possible points
- **FinalGrade:** Student final grade. Final grade = (Participation + Project 1 + Project 2 + Project 3) / 400 x 100


### If you have any issues or questions, please reach out to your colleagues on Slack.

![](https://media.giphy.com/media/4TtTVTmBoXp8txRU0C/giphy.gif)
