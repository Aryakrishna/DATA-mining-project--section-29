Using twitter to do analysis on Oscars 
=============

# OVERVIEW
In our day to day life we see machine learning and analysis of open data set useful to the developers across the world to build a tool to explore some useful information . We would like to use data from our   twitter accounts and to use the sentiment analysis on the data present on twitter regarding the current Oscars. With latest accusations in Oscars on it being white has sparked a great deal of debate. Somewhere positive about it and somewhere negative. Some hash tags like #OscarsSoWhite is causing a lot of backlash. Some has termed it as causing a genuine conversation.  

# DATA

Twitter using Tweepy API. 

Finding data to explore the analysis space is generally easy, as there are a plethora of open texts available to both train and test on. One typical target Twitter, is an interesting platform because the data sets can be large and diverse, but more importantly, the 140 character restriction, keeps tweets about to a sentence or so in length. That makes analysis easier on the one hand, because the chunks to classify are shorter and in plenitude (for example, analyzing an entire essay for statement can be much more complex), but on the other hand presents many issues with the data lacking linguistic structure, sufficient complexity, as well as the language being overloaded with shorthand, odd things like hashtags and other tokens that take up space (URLs) that may not (but could) directly add to assessing the sentiment of the tweet. Twitter provides an API to extract tweets from which a large dataset will be built.

We are planning to retrieve the data from twitter using Tweepy API (https://github.com/tweepy/tweepy). 



# RESEARCH QUESTIONS
We're going to explore a test set of tweets about Oscars, specifically tweets which included the hash tag #OscarsSoWhite,and the Tweepy API was used for obtaining the data from Twitter.
Exploratory data analysis of Twitter data.  
Development of API  to classify text; endpoints non-functional until classifiers complete  
Development of classifiers; creation of test and training sets; tuning of classifiers.   
Development of build and deployment script.  Development of API test harness.

# MODELS AND ANALYSIS

The models are described and the preliminary analyses will be performed in a Jupyter Notebook and development in python and soon we will post them in our GitHub repo under analysis.

# CODE AND APPLICATION
 
Will post the code in our GitHub repository and instructions on installation are in the README.md file at the root level soon.



we are team of three ,Arya Krishna, Srinivas Attili, Vennel Mudireddy we will be sharing our work among ourselves .
Arya will be taking care of development ,data analysis ,  Back end work consisted of an API that was created to provide data to the front end and to pull Twitter Connections and Srinivas and Vennel would work on data set, data analysis and UI development and together we are collaborating to check the progress of the project testing.
You will need to provide details on:



# PROJECT TEAM, DELIVERABLES AND CHECKPOINTS
These tables show  examples of the data that should go into each column and row.


## TEAM

| Team member | Roles and skills | Contributions |
|-------------|-------------------------|---------------------------------------------|
| Arya Krishna| API development ,data analysis, Python|  Web API ,Data Analysis  |
| Srinivas Attili| Data analysis ,Testing | build scripts , data analysis, testing |
| Vennel Mudireddy| Testing ,Data analysis  |  Data analysis, test harness; build scripts.|

## DELIVERABLES AND CHECKPOINTS





| Checkpoint date | Expected Deliverable                                                          | Responsible team member(s) | Checkpoint results                                                                                                                  |
|---------------|-------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
|2/13/16| Exploring data analysis of  Twitter API Access data set through standard authentication mechanisms .  | Arya Krishna, Srinivas Attili, Vennel mudireddy| Meets project proposal check point 1 |
|  3/15/16  | As of no We are creating a streaming script which collects data from twitter as per the twitter policy there are curtain   limitation on number of request you make per day. Using the API http://textprocessing.com/api/sentiment to see if initial results match our criteria. |  Arya Krishna, Srinivas Attili                   |   |
| 3/20/16 |   We Will upload the complete data set and initial project code . As per answer/update the research question it will depend upon the results we see in the initial analysis | Arya Krishna, Vennel mudireddy  |                      |
| 4/3/16 | Complete the coding and simultaneous testing will be done by group all the group members to ensure the quality of the result.  | Arya Krishna, Srinivas Attili |                      |
| 4/17/16 | Finalize the testing phase and check the results and submit for feedback. | Arya Krishna, Srinivas Attili  |           |
| 4/29/16 | To present a final report.  | Arya Krishna,Vennel mudireddy  |           |
