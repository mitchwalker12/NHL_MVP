# NHL_MVP
NHL_MVP is a tool using regression to predict the next NHL MVP. 

![Hockey](hockey.jpg)

## **Binder**
https://hub.gke2.mybinder.org/user/mitchwalker12-nhl_mvp-hknqvb9n/lab

## **How It Works**
1. Webscrapes & Parses data from hockey-reference.com.
  a. MVP Voting Data
  b. Player Statistics
  c. Team Statistics
2. Cleaning data using pandas.
3. Building a regression model based on the cleaned data.

## **How to Run the Program**
Program Instructions:

1. Access the above .ipynb files and download each of the three data sets. 
2. Save those data sets as a csv file. 
3. Save the nicknames.csv file in the same directory. 
4. Using pip install, ensure your virtual environment contains all the necessary dependcies listed in the requirements.txt file.
5. Ensure the necessary imports are included in the three python files.   <br>
    `import requests`   <br>
    `import os`   <br>
    `import shutil`   <br>
    `import time`   <br>
    `import numpy as np`   <br>
    `from bs4 import BeautifulSoup`   <br>
    `import pandas as pd`   <br>
    `from sklearn.linear_model import Ridge`   <br>
    `from sklearn.metrics import mean_squared_error`   <br>
6. Run the python files. 

## **Analysis Results**
Sidney Crosby was predicted to the next NHL MVP. 

## **Resources**
[mark down cheat sheet](https://www.markdownguide.org/cheat-sheet/)
