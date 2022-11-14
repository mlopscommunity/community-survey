# Overview
**Document status:** Working draft

Our goal is to create a survey that helps us, data science & MLOps practitioners, learn more about our community and (in the future) track how our community changes year-over-year.  Said differently - this is a survey for the community, by the community.  We designed this survey to gain an accurate understanding of we, the professionals designing, building and deploying **production** ML systems, individually and collectively are, the types of data and models we implement, the tools we use, and the challenges we face.  Specifically, this is NOT a vendor-led survey that pushes forward a specific perspective that advantages a vendor or group of vendors.

The anonymized responses (e.g., identifying information removed) will be made available as part of this repo.

This document provides an outline of the topics we want to understand from our community.  It is intended to spark discussion and drive alignment on set of topics and learning goals within each topic.

# Supporters and contributors
Below are the folks who are contributing and/or supportive of this effort.  Please feel encouraged to open a [PR](https://github.com/mlopscommunity/community-survey/pulls) with your name if you are supportive of the survey or want to contribute!

| Name                 | Contact Info                   |
|----------------------|--------------------------------|
| Eric Peter           | eric@ericpeter.com             |
| Demetrios Brinkmann  | demetrios@mlops.community      |
| Gonçalo Ribeiro      | g@ydata.ai                     |
| Jacopo Tagliabue     | jacopo.tagliabue@nyu.edu       |
| Duarte Carmo            | me@duarteocarmo.com      | 
| Ben Wilson           | benjamin.wilson@databricks.com |
| Han lee              | lee.hanchung@gmail.com         |
| Skylar Payne         | skylar@healthrhythms.com       |
| *Add your name here* |                                |

<!-- 
Copy this row to add yourself

| Name                    | Contact                 |

-->

# Timeline

TODO: Add actual dates

- Date 0: Engage with various community members to evangelize idea, identify contributors, get feedback, etc
- Date 1: Align on the topics & learning goals
- Date 2: Develop a core group of contributors
- Date 3: Survey draft written
- Date 4: Survey text finalized
- Date 5: Survey launched
- Date 6: Survey closed
- Date 7: Survey raw data available
- Date 8: Synthesis available

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

# Survey Topics

Below is the proposed list of survey topics and learning goals for each.  The survey will be max 15 minutes in length (ideally shorter), so the topics below will be prioritized for inclusion.

## Identify the personas within our community 

Beyond job title, who are we?  What skills do we have?  What responsibilities do we own?  What are our attitudes and perceptions towards/of MLOps?  What types of organizations do we work for?  What team structure(s) are we a part of?

**Indicative topics/questions**
- Current job & past titles
- Years & types of experience
    - DevOps, ML Research, Software Engineering, etc
- Current  responsibilities
    - Experimentation, productionization, etc
- Attitudes towards ML and MLOps
    - "MLOps is just DevOps", "MLOps should be an extension of DevOps", "MLOps is different from DevOps", "Software and ML should follow the same DevOps process", etc
- Familiarity with various ML and data concepts/topics
    - ML concepts: Feature Store, Model Registry, etc
    - Data concepts: Streaming, batch processing, etc
- Company details
    - Number of employees, industry, etc
    - Employer perceptions
- Team details
    - Number of people by role
- Community participation
    - Which communities?
    - Frequency of engagement
    - Reasons for engaging

## Tools that we use
Understand which ML and MLOps tools / frameworks are used by teams:
- Frequency of tool usage
- Use case for each tool
- Satisfaction with each tool
- Which tools would we (not) recommended?
- Effort for initial setup and ongoing maintenance

Understand the maturity of internal ML platforms or "paved paths"

TODO: Curate a list of tool categories and tool names.
TODO: Should we differentiate between tools (Pytorch, Notebooks, etc) and infrastructure (Kubernetes, etc)?  Or is the difference too blurred?

## Data stack
Understand the sources/sinks of data training and production 
- Frequency of each source's use
- Difficulty of using each source
- What each source is used for (training data, production, logs, etc)?
- Desired sources that can't be used

Understand the data infra & tools
- Frequency of use
- Satisfaction 

TODO: Flesh out list of data sources (REST API, production DBs, data lakes, etc)
TODO: Flesh out list of data tools (Spark, BigQuery, etc)

## ML utilization buy-in
Understand the business-related struggles of utilizing ML / DS solutions
- Process of project proposal
- Difficulties in navigating buy-in with stakeholders
- Approval and auditing processes for project work

## Project research
Understand where and how practitioners discover tools, methods, and examples
- Sources of knowledge
- References and examples to learn from
- Ideation validation processes (where and how are experiments conducted)
- Testing and vetting process (peer review, demo, etc.)

## SPIKE process
Tools and methods used in validating proposed architectures and approaches
- Tools and frameworks used
- Process of running experimental validation of ideas
- Time boxing and restriction of scope creep

## ML use cases

### Overview
Understand the broad strokes of the types and details of the use cases overall.  These questions will be asked as "approximately what % of your ML use cases[1] are the following?"

- Analytical (batch/offline) vs API-based (real time/online)
- Business use cases (pricing, recommendations, fraud, etc)
- Types of models (Transformers, XGBoost, etc)
- Types of data (tabular, unstructured text, images, video, time-series, etc)
- How model predictions are accessed by the end-user (within a report, BI tool, application, etc)
- Approach to releasing models and features (CI/CD, manual releases, etc)
- Feature freshness (milliseconds/realtime, hours, days, weeks, etc)
- TODO: Add others of interest

Understand the future view of these use cases - what will this look like in 3 years from now?

Other topics of interest
- Models that do / don't make it to production & why
- Which segments of the use cases are hardest to implement and why?

TODO: Significant effort is required here to ensure these responses are MECE (mutually exclusive and collectively exhaustive)

[1] **ML use case** is defined as *the set of input data, features, and model(s) required to deliver a final prediction that the end user sees.*  

### Details
A flaw in many existing surveys is that they ask respondents specific details, but ask these details as a generalization across all use cases.  This is known to produce poor quality (inaccurate) data since, as humans, generalizing is actually a surprisingly difficult task.  In order to collect accurate data on the "weeds" of how we use ML, this section will ask detailed information about a single specific use case.  The results will be aggregated and weighted according to the broad information collected in the previous section.

TODO: Add more details on the methodology

TODO: Flesh out this list of topics
- *Include all topics from the general use case overview*
- Time to deploy
- Time taken at each lifecycle stage
- Difficulty of each lifecycle stage
- What metrics you track
- Which roles (people) were involved
- Number of models used
- Number of features used
- Size of training data (GB, PB, etc)
- Volume of predictions
- Challenges faced and severity of each (TODO: need a good list here)
- Differences between the training and production environments (different code, etc) 

Challenges
- validate data is the same between train & prod
- validate feature logic is the same
- manage dependencies in code (libraries)
- mange dependencies between models or features version
- reproducibility
- monitor metrics
- speed of deployment

ML Lifecycle stages
TODO: Improve this draft
- Requirement definition
- Data identification
- Data cleaning
- Feature engineering / pre-processing
- Model training
- Model productionization
- Feature productionization
- Model deployment
- Feature deployment
- Monitoring

## Spending
*TBD - should we include this?  This could be interesting to track over time.*
Understand the data science budgets and what specifically companies are currently spending that budget on (tools, infrastructure, etc).
