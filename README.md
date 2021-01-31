# Finding the insight information on the rental business by a data-driven approach.
### Table of Contents 
1. [Project Motivation](#Project-Motivation)
2. [Description](#Description)
3. [Installation](#Installation)
4. [File Descriptions](#File-Descriptions)
5. [Results](#Results)

## Project Motivation
I do this project, due to my desire to finding insight information about the rental business. I am curious about these 3 questions:
1. What factors affect price fluctuations?
2. What factors affect customer satisfaction?
3. Can we find negative and positive reviews based on texts?

## Description
This project gives an insight information on the Airbnb rental business by using machine learning method. 
The answers of each question are provided inside the jupyter notebook file. 

## Installation
The project code should run with no issues using Anaconda versions 4.9.x and python versions 3.x. </br>
The tweet dataset are not in the github repository becaue of the file size. So you need to download from here:
https://www.kaggle.com/kazanova/sentiment140/version/1 </br>
After downloaded the tweet dataset, put it in the datasets folder as an example below: </br>
```
datasets/training.1600000.processed.noemoticon.csv
```
## File Descriptions
datasets/: The folder that contains dataset. <br/>
datasets/boston/listings.csv: The boston dataset. <br/>
datasets/boston/reviews.csv: The boston comment dataset. <br/>
datasets/seattle/listings.csv: The seattle dataset. <br/>
datasets/seattle/reviews.csv: The seattle comment dataset. <br/>
images/: The folder that contains images for explaination. <br/>
readme.md: README file. <br/>
airbnb_analysis.ipynb: The jupyter notebook file where the code and visualization are presented.

## Results
The results are discussed in my blog post: <br/>
https://medium.com/p/a31fc25d5b77/
