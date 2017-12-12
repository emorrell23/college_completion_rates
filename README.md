# Regression Model to Predict College Completion Rates using College Scoreboard API

For this project I used the college scoreboard API to find an interesting relationship and build a predictive model. The college scoreboard API is a collection of higher education data from the government that has a ton of data that spans a number of years and categories. The relationships to analyze are almost limitless.

The variable that I am interested in, my target variable, is the completion rate (or the percentage that students complete their degree) for given colleges. To investigate this variable, I built a regression model that aims to predict the completion percentage for a given college. In a nutshell, I tried a few different variations of a traditional machine learning model to find the best one, and then I will compare it to a neural network model. See the code in the jupyter notebook to see how exactly I went about doing that.

All data is from 2015, which is the most recent year that all data needed for model was available.




# Project Background


## Project 4 

Due Date: November 29, 2017


For this project you will assemble a dataset for investigating colleges and universities.  Fortunately, there is a large collection of higher education data from the government that is accessible through an API.  This service provides tons of data, from cost statistics to admission rates to instructional expenditures!

The data spans a number of years and categories, so simply deciding what data you want to look at and how you want to analyze will take some time.

A successful project will pull down data, perform thorough EDA and build *at least* one model.  (What you model is up to you, and remember that models can be predictive *or* inferential!).  You could also look at the possibility of clustering to identify different types of schools.

> **Pro tip:** The rate limit is quite high for the API service, but it is still a good idea to cache your data to local file once you have retrieved it.  This allows you to reload your data faster and work offline, not to mention just playing "nice" with the API service.

The main data documentation is available at [https://collegescorecard.ed.gov/data/documentation/](https://collegescorecard.ed.gov/data/documentation/). This page includes a detailed data dictionary as well as a couple of reports describing the data.  That page also links to the specific [API documentation](https://github.com/RTICWDT/open-data-maker/blob/master/API.md).

To use the API you will need to signup for a (free) API key on [https://api.data.gov/docs/](https://api.data.gov/docs/).  This page also includes links describing [API key usage](https://api.data.gov/docs/api-key/) and [rate limits](https://api.data.gov/docs/rate-limits/).


## Project Feedback + Evaluation

For all projects, students will be evaluated on a simple 4 point scale (0-3 inclusive). Instructors will use this rubric when scoring student performance on each of the core project requirements:

Score | Expectations
----- | ------------
**0** | _Does not meet expectations. Try again._
**1** | _Approaching expectations. Getting there..._
**2** | _Meets expecations. Great job._
**3** | _Surpasses expectations. Brilliant!_

For Project 4 the evaluation categories are as follows:

- **Organization**:	Clearly commented, annotated and sectioned Jupyter notebook or Python script. Comments and annotations add clarity, explanation and intent to the work. Notebook is well-structured with title, author and sections. Assumptions are stated and justified.
- **Exploratory Data Analysis**: A thorough exploratory data analysis has been conducted. Descriptive statistics, univariate and bivariate analysis, and plotting are skillfully used to explore connections across the dataset between features and targets.
- **Modeling Process**: Skillful and correct use of cross-validation, grid search, and goodness-of-fit metrics to evaluate candidate models. Assumptions and decisions in the modeling process are stated and justified. Use of correct modeling techniques in each challenge. Data is reproducibly and reliably transformed between training and test datasets.
