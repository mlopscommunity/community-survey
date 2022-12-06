# ORIGINAL LIST FROM README.MD

# KEPT FOR HISTORICAL PURPOSES - NOT CURRENT

This is the original list that was used as fodder for what we could ask.  

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
