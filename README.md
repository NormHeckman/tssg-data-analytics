![TSSG](https://github.com/mikec964/chelmbigstock/blob/master/TSSGwiki.png) This repository, **tssg-data-analytics** supports the **Data Analytics** subgroup of the Chelmsford, MA [Technical Skills Share Group](https://groups.yahoo.com/neo/groups/TSSG-Chelmsford/info) (TSSG). We meet every Wednesday in Acton or Chelmsford (3rd Wends of month) for a general/status meeting. We also have a working meeting every Friday in Acton. We're a group of professionals in the Chelmsford / Acton area learning Data Science. We work through various hands-on learning projects and seek to work on a longer term project to demonstrate our skills. Extensive notes on our groups past activites are in another GitHub repository. See the [ChelmBigStock TSSG wiki] (https://github.com/mikec964/chelmbigstock/wiki).

This repository contains information on data science project activites done within the [Kaggle Competions] (https://www.kaggle.com) as well as independant projects related to our learnings.

As a group, we have studied the [Kaggle Digit Recognizer] (https://www.kaggle.com/c/digit-recognizer) training competion.
Code for this competion can be run using Kaggle Scripts which support the execution of R, Python and other language code directly on the Kaggle website. Kaggle recommends new users start by working through the [Titanic: Machine Learning from Disaster] (https://www.kaggle.com/c/titanic) learning activity Many of us have also worked on that knowledge competition.

We have reviewed the benchmark example utilizing Random Forests. A random forest classifier is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and use averaging to improve the predictive accuracy and control over-fitting. Packages are available in many languages, R and Python for example. RandomForests can be sucessfully used by those with little statistical expertice.

Some of us are learning the R-language and have installed R and RStudio on our laptops.  Others have been learning Python and have installed Python and iPython Notebook/Jupyter from the [Anaconda distribution.] (https://store.continuum.io/cshop/anaconda/) Note that iPython support has transitioned to [Jupyter,] (https://jupyter.org) a platform that will support mulitple languages, Python, R, Julia and more.

We've looked briefly at the [Census Data Exploration]
(https://www.kaggle.com/c/2013-american-community-survey) open-ended knowledge challenge which includes mapping tools. We are are currently investigating the [San Francisco Crime Classification] (https://www.kaggle.com/c/sf-crime) knowledge challenge which asks specific questions, and provides an opportunity for exploring mapping. We are building an understanding of other participants scripts for analyzing the data and predicting the answers.

We have looked at some other worked examples from Kaggle. A summary will be added here real soon now.

We've returned to Kaggle in order to build skills with machine learning tools. The recommended starting point in Kaggle is the Kaggle Titanic challenge. Here are some How to Get Started Instructions for using the Titanic Getting Started Python learning code kaggle has provided :
Starting from Kaggle's Titanic Tutorial page, 
https://www.kaggle.com/c/titanic#getting-started
Here is an iPython starter Python tutorial
https://www.kaggle.com/omarelgabry/titanic/a-journey-through-titanic

You can get yourself a login on Kaggle.com and fill out a profile.
Then you can FORK the code and run it inside of Kaggle in your browser.
Please try to do this, as it avoids all the following detail trashing about.

If you still  insist on downloading the iPython notebook, you can do that. 

Note that Kaggle uses Python 3.x so ... at the anaconda prompt you need to 'activate py35' to switch form the default Python 2.7 to Python 3.x.
Install required package seaborn  at the anaconda command prompt.
 'conda install -c anaconda seaborn=0.7.1'

Download the notebook file from code link then download code
https://www.kaggle.com/omarelgabry/titanic/a-journey-through-titanic/code
by clicking the download button
You will get the file: 
\_\_notebook\_\_.ipynb
put his file into a local directory on your workstation or pc. For exampie:
c:workspace/Titanic-iPython/iPython-notebook
Then download the data files from the the data link of
https://www.kaggle.com/c/titanic
go to
https://www.kaggle.com/c/titanic/data
and download the three files:
train.csv
test.csv
gender_submission.csv
Put these three files in a local directory on your workstation or pc. For example:
c:/workspace/Titanic-iPython/input

Then (assuming you have installed Anaconda on your local machine) open an anaconda command prompt.
Using 'cd' change directory to the directory containing the iPython notebook
cd c:\workspace\Titanic-iPython\ipython\_notebook
Then type
jupyter notebook \_\_notebook\_\_.ipynb
Then a browser window in your default browser will open showing the notebook.

We have sought to work together on a longer term project to analize social media data. Lots of examples of appoaches, methods, and code snipits are avalable on Kaggle.com and the  web. Twitter data is a good candidate. We have used cree.py, and Open Source Intelligence Automation tool (OSINT) which only gathers Tweets which have geocodes attached. MOZDEH is another tool we have used.  We are looking some other open source tools to collect tweets. There are also 12 databases of Twitter data currently available on Kaggle. Some code has been adapted from a Kaggle contributor and can be run locally on a pc under Jupyter/iPython which can read Twitter files collected by cree.py.  The intention is to build a collection of tools that can collect tweets, analyze, cross-corelate with other data sources.  We will leave behind documentation and code demonstrating our skills.  Thereby providing benefit to the entire project team who understands and has contributed.  A tutorial startup repository Twitter_Analysis is also available on this account.
