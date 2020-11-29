---
title       : Introduction to Data Careers
subtitle    : An Overview of Data Science
author      : Junaid Butt
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---
<style>
.title-slide {
  background-color: #FFFFFF; /* #EDE0CF; ; #CA9F9D*/
}
</style>


## Table of Contents

1. What is Data Science?
2. What types of jobs exist in Data Science today?
3. What skills are required to be an effective Data Scientist?
4. How do I get into Data Science?
5. Who's Hiring?

--- .class #id 

## What is Data Science? 

* The term 'Data Science' was first coined by DJ Patil (LinkedIn) and Jeff Hammerbacher (Facebook).

  "_I was at LinkedIn building the data team and Jeff     Hammerbacher was bustling at Facebook's data team... One of the things we realised was that we didn't know what to call ourselves...Do you call yourself an analyst? It feels too Wall Street. A research scientist or statistician? Feels too academic..._" - **DJ Patil**

  "_The most important thing is how you use data to interact with the world, study it and try to come up with new things..._" - **DJ Patil**

--- .class #id

## What is Data Science? 
### Intersection of Mathematics and Computer Science

* This definition is fine as a philosophical definition but if we review job descriptions, you get an idea of what the industry considers to be data science.

* Drew Conway's Data Science Venn Diagram



--- .class #id

## What is Data Science? 
### Intersection of Mathematics and Computer Science

<img src="assets/img/conway_datascience_venn_diagram.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="550px" height="500px" style="display: block; margin: auto;" />

--- .class #id

## What types of jobs exist in Data Science today?


* For the purposes of this talk we're going to centre our discussion around 3 major archetypes. To avoid confusion, I'm going to use the umbrella term "data person" when referring to all these roles.



--- .class #id

## What types of jobs exist in Data Science today?

* Data Analyst/ BI analyst:
  * Mainly responsible for the cleaning, organising, mining and visualising of data in order to generate insights from the data. Most general type of Data Scientist and their work offers the business a reliable and consistent view of the data.
  * Key Skills: Excel/ Google Sheets, SQL, basic knowledge of programming languages and visualisation tools (Tableau). 

--- .class #id

## What types of jobs exist in Data Science today?

<img src="assets/img/revolut_data_analyst_job_description.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" width="500px" height="500px" style="display: block; margin: auto;" />

--- .class #id

## What types of jobs exist in Data Science today?

* Data Scientist/ Statistical Modeler:
  * Responsible for digging deeper into data to perform inferential analysis and build statistical models.
  * Key Skills: SQL, Python/R/Julia, REST API and App development (Flask and Shiny), Version control/Git, distributed computing and knowledge of statistical algorithms. 

--- .class #id

## What types of jobs exist in Data Science today?

<img src="assets/img/monzo_datascience_job_description.png" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" width="500px" height="500px" style="display: block; margin: auto;" />

--- .class #id

## What types of jobs exist in Data Science today?

* Data Engineer/ ML Engineer:
  * This is a crucial role because it creates and manages the data science ecosystem. Without this system being properly set up, no effective work in Data Science can be achieved.
  * Key Skills: Python, Data Structures, ML algorithms, REST API and App Development, Virtualisation/ Docker/ Kubernetes, distributed computing, workflow management, Testing (Unit/ Integration).

--- .class #id

## What types of jobs exist in Data Science today?

<img src="assets/img/tractable_mlengineer_job_description1.png" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" width="450px" height="450px" style="display: block; margin: auto;" /><img src="assets/img/tractable_mlengineer_job_description2.png" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" width="450px" height="450px" style="display: block; margin: auto;" />

--- .class #id

## What types of jobs exist in Data Science today?

<img src="assets/img/facebook_mlengineer_job_description.png" title="plot of chunk unnamed-chunk-5" alt="plot of chunk unnamed-chunk-5" width="550px" height="500px" style="display: block; margin: auto;" />

--- .class #id

## Cross Functional or Specialised

* In product led technology companies, there are cross functional teams of software engineers, product managers and Data Scientists.

* It is less common to see Data Scientists/ Data Analysts and Data Engineers in their own dedicated functions.

* For most companies, the data revolution is underway and is in different stages - this is true for start ups as well.

---  &checkbox

## Quiz

Which of the 3 Data Science roles that we've discussed today would be responsible for setting up and maintaining a Data Warehouse?

1. Data Analyst
2. Data Scientist
3. _Data Engineer_

*** .hint

This would be a data architecture decision which would affect all aspects of the data workflow.

*** .explanation

This would traditionally be a Data Engineer's job.

--- .class #id

## What are the skills required to be an effective Data Scientist?

* Programming:
  1. Fundamental - We require databases and require skills like SQL to deal with data that can't be held in spreadsheets.
  2. Programming languages like Python/ R/ Julia are necessary to extract, transform, model and visualise data.
  3. Visualisation tools like Tableau/ Looker.
  4. What about purpose built tools like SPSS, Alteryx, etc? 

--- .class #id

## What are the skills required to be an effective Data Scientist?

* Statistical Literacy:
  1. Once we have good data and tools for analysing data we need an understanding how to effectively interrogate our data.
  2. The general Data Science workflow can be described by the PPDAC cycle


--- .class #id
## What are the skills required to be an effective Data Scientist?

<img src="./assets/img/ppdac_cycle.png" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" width="550px" height="500px" style="display: block; margin: auto;" />

--- .class #id

## What are the skills required to be an effective Data Scientist?

* Statistical Literacy:
  1. Formal methods: A/B Testing, Experimental Design, Probability theory and Statistical Modeling techniques.
  2. Data Wrangling: A key skill which differentiates the experienced and inexperienced Data Scientist.
  
* General Workflow:
  1. Git and Version control
  2. REST API and web app development/ deployment

* Visualisation and Communication
* Passion!


--- .class #id

## How do I get into Data Science?

### Effective Ways to Develop Knowledge

* You don't need a Mathematics or Computer Science Degree to do this!

* Courses
  * Statistics 110: Probability by Joe Blitzstein
  * Andrew Ng Coursera Series on Machine Learning
  * Richard McElreath Statistical Rethinking
  * Introduction to Statistical Learning by Hastie and Tibshirani
  * Linear Algebra 18.06 by Gilbert Strang

--- .class #id

## How do I get into Data Science?

### Effective Ways to Develop Knowledge
* Key Books
  * Art of Statistics by David Spiegelhalter (General)
  * Probability and Statistics for Data Science - Norm Matloff
  * Applied Predictive Modeling - Max Kuhn
  * Introduction to Data Mining - Kumar et al.
  * Deep Learning for coders with fastai and Pytorch - Jeremy Howard
  * Python Data Science Handbook - Jake VanderPlas
  * Python for Data Analysis - Wes McKinney
  * Probability and Statistics - Morris Degroot

--- .class #id

## How do I get into Data Science?

### Effective Ways to Develop Knowledge

* Follow influential Data Scientists in the community:
  * StatQuest on Youtube 
  * Hadley Wickham
  * Julia Silge
  * Andrew Gelman
  * David Robinson
  * Jake VanderPlas


--- .class #id

## How do I get into Data Science?

* If you have a good foundation of programming and statistical skills then you can do the following   

* Projects - Like Software Engineering, it helps to have a portfolio of Data Science projects in which you've demonstrated key technical skills.

* Build web apps with statistics/ ML integrated - Flash/ Shiny. These don't have to be ground breaking or original!

* Be involved in community Data Science initiatives and activities.


--- .class #id

## Future of Data Science - Where I think the field is going

* Emergence of Data Science tools which are abstracting more and more of the traditional Data Science workflow.
* General move toward Data Engineering.
* Core Data Science work is moving to specialised subjects (NLP, Graphical methods, Reinforcement Learning, Computer Vision etc). 
* I personally recommend Data Engineering if you are intrigued by Data Science but are not in love with statistics. 


--- .class #id

## Who's Hiring?

* Most companies are hiring for data related roles. The notable companies that are hiring for Data Scientists year round are:
  - Facebook
  - Monzo
  - Deliveroo
  - Supermarkets (Tesco/ Sainsburys, etc)
  - Consultancies (EY, Mckinsey, PWC, etc)
  - Microsoft/ IBM
  - Many more
* Many start ups are also hiring for data related roles.

--- .class #id

## Discussion Questions
### Choose a Question in Groups and Have a Go!

1. You work at a SAAS company and your product manager comes to you and says "Signups to the platform are down to the lowest point of the year - what's happening?". What steps do you take to look into this?

2. Uses of your product have been declining recently - you suspect it is because customers are displeased with the customer experience, your CEO remarks "It makes no sense, our NPS scores are very high". What is the problem with this statement? How would you investigate what's happening?

3. You work at a newspaper and have built a new recommendation engine which suggests stories to users as they browse through your website. One of the journalists feels that the new algorithm does not promote their articles fairly with respect to others and has scheduled a meeting with you to speak about this - how do you prepare for this meeting?

4. If you don't like the look of any of the above - solve this $latex f(x) = \int_{-\infty}^{\infty} e^{-\frac{1}{2}x^2} dx $

--- .segue bg:grey

## Thank you!
