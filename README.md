# DS 4002 Project 1

## For our first project, we are testing the following hypothesis: there are more fraudulent job postings (as a percentage) for remote jobs than in-person jobs. Our hypothesis is motivated by the increase in remote jobs since the start of the COVID-19 pandemic. To help navigate our repository, adhere to the following sections. The "SOURCE" section shows how we install, build, and use our code. The "DATA" folder will enable you to see our data dictionary, a link to the Kaggle source, and notes about how we use the data. The "FIGURES" folder contains all of the figures produced and summarizes the takeaways. The "REFERENCES" section acknowledges the sources for our analysis. 

## SRC 
### Installing / Building Code
The primary source code for preparing the data for Naive Bayes can be found here as well as in the SRC Folder:
https://rpubs.com/drshah96/629986

### Usage of Code
After building the Naive Bayes model, it will necessary to scrape data from Glassdoor to run it through the model. 

## DATA 
### Data Dictionary
<img width="387" alt="Screen Shot 2023-02-23 at 8 55 44 AM" src="https://user-images.githubusercontent.com/104598450/220928112-d1a16484-94c4-44ac-b7f6-0a5091063914.png">
<img width="386" alt="Screen Shot 2023-02-23 at 8 55 55 AM" src="https://user-images.githubusercontent.com/104598450/220928133-26d7f93c-9cf2-4760-b5c5-5e426d6003a1.png">

### Link to Data
https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction

### Relevant notes about the use of data
While there are clearly many variables in our dataset, we are training our model based on job description exclusively, so we recommend dropping the rest of the columns.

## FIGURES 
### Table of Contents

## REFERENCES 
D. Abril, “Fake job postings are stealing applicants’ money and identities,” The Washington Post, December 22, 2022.  [Online]. Available: https://www.washingtonpost.com/technology/2022/12/22/job-posting-scam-tips/. [Accessed: February 9, 2023].

D. Shah, “Author Text Classification using Naive Bayes Algorithm,” June 19, 2020. [Online]. Available: https://rpubs.com/drshah96/629986. [Accessed: February 21, 2023].

R. Benjamin, “Scraping Glassdoor using Selenium and Python 2022,” July 9, 2022. [Online]. Available: https://medium.com/@benjaminrohan010/scraping-glassdoor-using-selenium-and-python-2022-bd0065775aec. [Accessed: February 21, 2023].

S. Bansal, “Real / Fake Job Posting Prediction,” February 28, 2020. [Online]. Available: https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction. [Accessed: February 9, 2023].

S. Loukas, “Text Classification Using Naive Bayes: Theory & A Working Example,” Towards Data Science, October 12, 2020. [Online]. Available: https://towardsdatascience.com/text-classification-using-naive-bayes-theory-a-working-example-2ef4b7eb7d5a. [Accessed February 9, 2023].
