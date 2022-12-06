# Overview
**Document status:** Working draft

Our goal is to create a survey that helps us, data science & MLOps practitioners, learn more about our community and (in the future) track how our community changes year-over-year.  Said differently - this is a survey for the community, by the community.  We designed this survey to gain an accurate understanding of we, the professionals designing, building and deploying **production** ML systems, individually and collectively are, the types of data and models we implement, the tools we use, and the challenges we face.  Specifically, this is NOT a vendor-led survey that pushes forward a specific perspective that advantages a vendor or group of vendors.

This document provides an outline of the topics we want to understand from our community.  It is intended to spark discussion and drive alignment on set of topics and learning goals within each topic.

# Objectives & goals

Specifically, our goals are:
* Develop a ~10 minute survey that provides a neutral, vendor-agnostic view of _who_ is in our community and _why and how_ MLOps is applied.
* Publish an annual report on the `State of MLOps` based on the survey results
* Survey 1,000 data science practitioners who are representative of the broader community (per year)
* Provide open-source access to the (anonymized) data
# Supporters and contributors
Below are the folks who are contributing and/or supportive of this effort.  Please feel encouraged to open a [PR](https://github.com/mlopscommunity/community-survey/pulls) with your name if you are supportive of the survey or want to contribute!

| Name                 | Contact Info                   |
|----------------------|--------------------------------|
| Eric Peter           | eric@ericpeter.com             |
| Demetrios Brinkmann  | demetrios@mlops.community      |
| Gonçalo Ribeiro      | g@ydata.ai                     |
| Jacopo Tagliabue     | jacopo.tagliabue@nyu.edu       |
| Duarte Carmo         | me@duarteocarmo.com            | 
| Ben Wilson           | benjamin.wilson@databricks.com |
| Han lee              | lee.hanchung@gmail.com         |
| Skylar Payne         | skylar@healthrhythms.com       |
| Niall Murphy         | niallm@gmail.com               |
| Jeffrey Luppes       | jeffluppes@gmail.com           |
| Andreea Munteanu     | andreeamihaelamunteanu@gmail.com|
| Laszlo Sragner       | laszlo@hypergolic.co.uk        |
| Elena Samuylova      | elena.samuylova@evidentlyai.com|
| *Add your name here* |                                |

<!-- 
Copy this row to add yourself

| Name                    | Contact                 |

-->

# Timeline

We are working backwards from an April 2023 release date for the report.  We are hopeful that our proposed KubeCon talk on this survey will be accepted.

- November 7 - 18: Engage with various community members to evangelize idea, identify contributors, get feedback, etc
- November 22: Finalized list of topics & learning goals
- December 9: First draft of survey text written
- December 10 - 22: Collect feedback on the draft survey text
- December 23 - January 5: Holiday break
- January 13: Survey release candidate #1 available as a web link
- January 13: Finalize list of incentives & distribution plan
- January 16 - 20: Live trials of survey with ~10 people to confirm length, identify bugs / unclear wording
- January 23 - 27: Finalize programming
- January 27 - February 10: Buffer for delays ;-)
- February 13: Survey go-live (tbd plan for distribution)
- March 3: Survey closed 
- March 17: First draft of survey analysis (e.g., annual report / blog post)
- March 17 - April 7: Refine survey analysis
- April 7 - 21: Buffer for delays ;-)
- April 21: Public release

# Want to help?

Interesting in helping out?  Below are some areas we have identified, but we encourage pull requests on this repo if you have another idea.  If you want to discuss, reach out to [Eric Peter (eric@ericpeter.me)](mailto:eric@ericpeter.me) or on [MLOps Slack](https://go.mlops.community/slack) at @Eric Peter.
## Minutes of effort
- Share the survey link to your network (once published)
- Submit a PR to add something that is missing or correct an error

## Hours of effort
- Help define & refine the topics & questions
- Take ownership of a specific define & refine the lists that form answer choices [LINK TO LISTS]()
- Volunteer as a QA tester
- Volunteer to take the survey (or a portion of the survey) live with a moderator (to help us refine the clarity of the questions & answers)

## Days of effort
- Participation incentives: define and curate incentives that will be raffled off in order to encourage participation
- Conduct data analysis once responses are collected (looking at you data scientists ;-)
- Write the report/synthesis of the results as a blog post, or ...

## Monetary assistance
- Pay for a license for a survey tool with maxDiff question types + advanced piping and branching logic (Qualtrics, etc)
- Donate a participation incentive 

# Survey length
Based on feedback from the community, a ~10 minute survey is ideal and would maximize participation likelihood.  Beyond length, we will make most questions optional so that participants can pick and choose questions if they are rushed or prefer not to answer.  Progress will be shown throughout.

# Survey Topics
Based on discussions with many in the community, the below topics were most frequently mentioned as items folks hoped to learn about the community / were perceived as most valuable to learn about the community.

Each topic has:
* Estimated timing
* What we want to learn
* Outcomes we hope to achieve by learning
* Rough draft list of questions
# Who we are: 5 mins
## [2 mins] Basic demographics of person & company 
### What do we learn / get by asking this?
* Get a baseline view of the types of orgs that are applying MLOps
* Get a baseline view of how ML teams are structured & who they work with
* Use as filters to analyze other questions
### Questions
* What is your current job title?
* What bucket does your role fall in?
    * ML Engineer
    * Data Scientist
    * Software Engineer
    * Data Engineer
    * SRE/DevOps
    * Researcher
    * Data Analyst
* What industry do you work in?
* What type of company?
    * Startup
    * Big tech
    * Enterprise [need better name]
* How many FTE in your company (number of people)?
* How many FTE on your team?
* How many FTE working on data science & machine learning?
* Where in your organization does your team sit?
    * Within central services
    * Part of a business unit
    * other??  how do we make this question relevant to startup & big E?
* Which other roles do you collaborate with?
* Where do those people sit?
    * Your team
    * Other teams
* Rate your organization's maturity [1 to 7 scale]
    * Data science
    * MLOps
    * DevOps 
    * Software engineering

## [3 mins] Suss out where our members lie on the spectrum of "I know more data science (algorithms, math, etc) to I know more engineering (infrastructure, software, etc)" and the relative importance of the associated skills.

### What do we learn / get by asking this?
* Double-click into *what* each job title actually means in terms of experience and skills
* Understand the perceived importance of each skill to success
* Understand where educational gaps are, and thus, what educational materials we need
* Help individuals determine where they should invest their personal educational effort

### Questions
* How many years of experience do you have with the following areas?
    * Backend engineering (infra, APIs, etc)
    * SRE/DevOps (reliability, etc)
    * Data pipelines (ETL, ELT, etc)
    * Streaming data
    * Algorithm research & development
    * Algorithm selection
    * Frontend engineering
    * WHAT ELSE??
* How (un)important is each in order to be successful in __your job__?
* How (un)important is each in order to be successful in __your overall team's success__?
# [4 mins] ML last use case

NOT FINISHED - this section asks about "the last use case where MLOps was involved" with the intent of building a baseline of how MLOps actually gets applied
### What do we learn / get by asking this?
* Who (roles) is involved with each area of responsibility for MLops
* Length of time for different stages of the process
* Understand which tools are actually used
* Understand which types of data are actually used
* types of models
* where predictions are exposed to users?

### Questions

* What is custom built?

- Analytical (batch/offline) vs API-based (real time/online)
- Business use cases (pricing, recommendations, fraud, etc)
- Types of models (Transformers, XGBoost, etc)
- Types of data (tabular, unstructured text, images, video, time-series, etc)
- How model predictions are accessed by the end-user (within a report, BI tool, application, etc)
- Approach to releasing models and features (CI/CD, manual releases, etc)
- Feature freshness (milliseconds/realtime, hours, days, weeks, etc)
- TODO: Add others of interest

# [1 mins] Make it fun

### What do we learn / get by asking this?
* Quotes to make our lives (and the report) more fun :-)

### Questions
* Open ended questions such as
    * Top frustration
    * Favorite thing
    * Piece of advice to others
    * what else??


