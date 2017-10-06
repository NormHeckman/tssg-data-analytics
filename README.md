![TSSG](https://github.com/mikec964/chelmbigstock/blob/master/TSSGwiki.png) This repository, **tssg-data-analytics** supports the **Data Analytics** subgroup of the Chelmsford, MA [Technical Skills Share Group](https://groups.yahoo.com/neo/groups/TSSG-Chelmsford/info) (TSSG). We meet Wednesday in Acton or (Chelmsford  on the 3rd Wed of each month) for a general/status meeting. We also have a working meeting every Friday in Acton. We're a group of professionals in the Chelmsford / Acton area learning Data Science. We work through various hands-on learning projects to develop our technical skills. Extensive notes on our groups past activites can be found in the [ChelmBigStock wiki](https://github.com/mikec964/chelmbigstock/wiki) and GitHub repository and at the [TSSG wiki](https://github.com/mikec964/chelmbigstock/wiki).

This tssg-data-analytics repository contains information on our team's recent data science project activites related to the [Kaggle Data Science Competions](https://www.kaggle.com).

####Kaggle.com Website Educational Resource
The [Kaggle website](www/kaggle.com) contains data science challenges, tutorials, code and data. It is **the** recommended site for learning data science. Code for those competions can be run using Kaggle Scripts which support the execution of R, Python and other language code directly on the Kaggle website. We have learned from studying the tutorials and other participants scripts for analyzing data and predicting results.

#####Titanic: Machine Learning
Kaggle recommends new users start by working through the [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic) learning activity Many of us have worked through that tutorial competition. We have reviewed their benchmark example utilizing Random Forests in R. A Random Forest classifier is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. Random Forests can be sucessfully used by those with little statistical expertice. Some of us are learning the R-language and have installed R and RStudio on our laptops.

Kaggle now provides a [How to Get Started](https://www.kaggle.com/c/titanic#getting-started) page of instructions. Try the [iPython Starter Tutorial](https://www.kaggle.com/omarelgabry/titanic/a-journey-through-titanic) Request a login on Kaggle.com. Then you can **FORK** code experiment with it and and run it yourself on your account on Kaggle in your browser.

#####Titanic: Machine Learning running on your PC or Workstation
You can download that iPython notebook. Here are some 'how to' instructions:
The recommended Python instalation is the [Anaconda Python](https://www.continuum.io/downloads) package.
Note that Kaggle uses Python 3.x so you may need to select that version. If you have the default 2.7 as well as have installed 3.x, then at the anaconda prompt you need to enter **'activate py35'** to switch form the default Python 2.7 to Python 3.x.

Install required package seaborn  at the anaconda command prompt.
 **'conda install -c anaconda seaborn=0.7.1'**

Download the [iPython Starter Tutorial](https://www.kaggle.com/omarelgabry/titanic/a-journey-through-titanic) notebook file by clicking the download button
You will get the file: **\_\_notebook\_\_.ipynb**
Put his file into a local directory on your workstation or pc. For exampie:
**c:workspace/Titanic-iPython/iPython-notebook**
Then download the data files from the the **Data** tab on the [Titanic Challenge](https://www.kaggle.com/c/titanic) web page. Select and download the three files: **train.csv**,   **test.csv**, and **gender_submission.csv**.  By clicking on the **Download File** button. Put these three files in a local directory on your workstation or pc. For example: **c:/workspace/Titanic-iPython/input**

Then open an anaconda command prompt.
Using **'cd'** change directory to the directory containing the iPython notebook
**cd c:\workspace\Titanic-iPython\ipython\_notebook**
Then type **jupyter notebook \_\_notebook\_\_.ipynb**
Then a **Jupyter** tab in your default browser will be opened showing the notebook you downloaded. 

#####Handwritten Digit Recognizer
As a group, we have also studied and worked through the [Kaggle Digit Recognizer](https://www.kaggle.com/c/digit-recognizer) training competion.

#####Census Data Exploration & San Francisco Crime Classification
We looked briefly at the [Census Data Exploration](https://www.kaggle.com/c/2013-american-community-survey) open-ended knowledge challenge which includes mapping tools. We briefly investigated the [San Francisco Crime Classification](https://www.kaggle.com/c/sf-crime) knowledge challenge which asks specific questions, and provides an opportunity for exploring mapping.

#####Social Media (Twitter) Data Analysis
Lots of examples of appoaches, methods, and code snipits are avalable on Kaggle.com and the  web. Twitter data is a good candidate. We have used **cree.py**, and Open Source Intelligence Automation tool (OSINT) which gathers Tweets by location and **mozdeh** to gather any Tweet.  Kaggle has more than 12 databases of Twitter data available. A repository [**Twitter_Analysis**](https://github.com/NormHeckman/Twitter_Analysis) has been setup to analize social media (Twitter) data. Code has been adapted from a Kaggle contributor and can be run locally on a pc under Jupyter/iPython which can read Twitter files collected by cree.py.  This code could be extended to perform more analysis and or to cross-correlate with other data sources.

#####Machine Learning - Member Contributions
Several members are working on personal projects and coursework and have their own Social Media presence.
[Andy Webber](https://github.com/andygwebber) has demonstrated Machine Learning techniques on his GitHub account.
