### Table of Contents

# MeAndFitbit

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The following libraries were installed as part of this project:


  -  seaborn Version: 0.11.0
    -  [Seaborn](https://seaborn.pydata.org/) is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
  
  -  xgboost   Version: 1.5.1
    -  [XGBoost](https://xgboost.readthedocs.io/en/stable/) is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework.



## Project Motivation<a name="motivation"></a>

The intention of this project is to examine my personal Fitbit data and look for larger trends that the app typically can not provide. Do my internal interpretations of my activity align with the data? The intention is not to improve fitness, lose weight or make changes to my habits. This is intended to discover the truth about my Fitbit utlization. 

1. How consitently do I wear my Fitbit? 
2. Does the weekday/weekend utilization differ? How?
3. Do I get more or less steps based on the time of year?  Winter in Minnesota means complete darkness by 5:00pm so my activity changes from walking to eliptical. 
4. 

The data used was downloaded from Fitbit using the steps [here](https://help.fitbit.com/articles/en_US/Help_article/1133.htm).  Only my 2021 Activity data for this analysis. 

## File Descriptions <a name="files"></a>

There is 1 notebook associated with this project and 1 data file.  The notebook is an high-level exploratory analysis of my personal Fitbit data. Other code may be added to this repository in the future if my curiousity grows. 

## Results<a name="results"></a>

Much of the analysis was done by simply doing a visual exploration of the data.  XGBoost regression was use to compare the feature importance of weekdays vs. weekends. No fine tuning of hyperparameters was done.  This is meant to be a high level project and first look at the data.

The findings of this projects can be found at the blog post available [here](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Template for the README file was provided by Udacity. 

Use of the Fitbit data is subject to the Terms of Service documented [here](https://dev.fitbit.com/legal/platform-terms-of-service/).

Other acknowledgements of code leveraged via Stackoverflow are documented within the code itself.  Thank you Stackoverflow! 



