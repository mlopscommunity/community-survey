The draft survey itself.

# Survey length
Based on feedback from the community, a ~10 minute survey is ideal and would maximize participation likelihood.  Beyond length, we will make most questions optional so that participants can pick and choose questions if they are rushed or prefer not to answer.  Progress will be shown throughout.

# Survey Topics
Based on discussions with many in the community, the below topics were most frequently mentioned as items folks hoped to learn about the community / were perceived as most valuable to learn about the community.

Each topic has:
* Estimated timing
* What we want to learn
* Outcomes we hope to achieve by learning
* List of questions to be asked

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

This section asks about "the last use case where MLOps was involved" with the intent of building a baseline of how MLOps actually gets applied.

### What do we learn / get by asking this?
* Help understand the types of real world ML deployments where MLOps is applied

### Draft questions
* What is the business use case?
* Who (roles) is involved with each part of the process
* Length of time for different stages of the process
* Which tools are used?
* What data sources are using in training and/or production environments?
* What is the ML application?
    * Regression
	* Classification
	* Probabilistic classification
	* Retrieval
	* Ranking/re-ranking
* What types of data?
    * tabular
    * images
    * text
    * video
    * audio
    * time series
    * OR multi-modal
* What is your model's architecture?
    * boosted (XGboost)
    * random forest / ensemble model
    * linear model, regression, elastic net
    * encoder<>decoder or recurrent model
    * convolution model
    * transformer model
    * graph type of model
* Approach to releasing models and features (CI/CD, manual releases, etc)

* Who is the end user of the prediction(s)?
    * Internal user
    * Customer
    * Other [please specify]

* Where are the prediction(s) displayed to the end user?
    * Dashboard or report (Tableu, etc)
    * Application (web)
    * Application (mobile)
    * Database table (SQL, etc)
    * Other [please specify]

* How often does the model's input data change? 
| | % of features |
| ----- | ----- | 
| Milliseconds | __ |
| Seconds | __ |
| Minutes | __ |
| Hours | __ |
| Days | __ | 
| Weeks | __ |
| Months | __ | 

* How often are the model's predictions recalculated?
| | Current state | Ideal state (ignoring any current constraints)|
| ----- | ----- | ----- | 
| Milliseconds | [  ] | [ x ] |
| Seconds | [  ] | [  ] |
| Minutes | [ x ] | [  ] |
| Hours | [  ] | [  ] |
| Days | [  ] | [  ] |
| Weeks | [  ] | [  ] |
| Months | [  ] | [  ] |

* Would you consider this use case?
    * Batch/offline
    * Real time/online

# [1 mins] Make it fun

### What do we learn / get by asking this?
* Quotes to make our lives (and the report) more fun :-)

### Questions
* User choose of open ended questions:
    * What is your top frustration with MLOps?  Why?
    * What is your favorite MLOps tool?  Why?
    * What is one piece of advice you'd offer to others applying MLOps?
    * [OTHERS?]


