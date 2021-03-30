# Finding the insight information on the rental business by a data-driven approach.
### Table of Contents 
1. [Project Motivation](#Project-Motivation)
2. [Description](#Description)
3. [Installation](#Installation)
4. [Libraries](#Libraries)
5. [File Descriptions](#File-Descriptions)
6. [Results](#Results)
7. [Resources](#Resources)

## Project Motivation
I create this project, due to my desire to finding insight information about the rental business. I am curious about these 3 questions:
1. What factors affect price fluctuations?
2. What factors affect customer satisfaction?
3. Can we find negative and positive reviews based on texts?

## Description
This project finds insight information on the Airbnb rental business by using the machine learning method. </br>
The answers of each question are provided inside the jupyter notebook file.

## Installation
The project code should run with no issues using Anaconda versions 4.9.x, python versions 3.x., and seaborn versions 0.11.x </br>
The tweet dataset are not in the github repository becaue of the file size. So you need to download from here:
https://www.kaggle.com/kazanova/sentiment140/version/1 </br>
After downloaded the tweet dataset, put it in the datasets folder as an example below: </br>
```
datasets/training.1600000.processed.noemoticon.csv
```
## Libraries
* pandas
* numpy
* sklearn
* nltk
* bs4
* scipy
* re
* math
* statsmodels
* matplotlib
* seaborn

## File Descriptions
```datasets/```: The folder that contains dataset. <br/>
```datasets/boston/listings.csv```: The boston dataset. <br/>
```datasets/boston/reviews.csv```: The boston comment dataset. <br/>
```datasets/seattle/listings.csv```: The seattle dataset. <br/>
```datasets/seattle/reviews.csv```: The seattle comment dataset. <br/>
```images/```: The folder that contains images for explanation. <br/>
```readme.md```: README file. <br/>
```airbnb_analysis.ipynb```: The jupyter notebook file where the code and visualization are presented.

## Results
- Factors that affect price fluctuation, customer satisfaction, and the sentiment of each review based on texts.
More result details are discussed in my blog post: <br/>
https://medium.com/@Alcos1031/how-to-find-the-rental-business-insight-information-by-a-data-driven-approach-a31fc25d5b77

## Resources
* Boston dataset <br/>
https://www.kaggle.com/airbnb/boston
* Seattle dataset <br/>
https://www.kaggle.com/airbnb/seattle
* Tweets dataset <br/>
https://www.kaggle.com/kazanova/sentiment140/version/1
