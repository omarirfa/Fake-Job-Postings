# Fake Job Postings (Results)
This directory contains the insights gained from the data, confusion matrices for the algorithms utilized, and their classification reports. 
Logisitic regression (LR) had very similar results to multinomial naive-bayes (MNB) in terms of precision, recall and F1-score. While, random forest had the worst F1-score of 0.47. SVM had a decent score of 0.72.
LR and MNB had the best result for differentiating between fraudulent and real jobs. But keep in mind this result is subject to change based on data availability and improvements suggested.

Note: NA roles indicate NaN values where the person has not provided a role in the posting.


### Graphs
- imbalanced-dataset emphasizes that the dataset is highly imbalanced. There are more real job postings as compared to fake jobs.
- country-wise-jobs shows the top 11 countries where jobs have been posted. The most jobs have been posted in US, Great Britain and Greece.
- fraud-based-on-employment-type reveals the different employment types (Other, Full-time, NA, Part-time, Contract and Temporary) that were analyzed. Fraudulent jobs were found mainly for Full-time, NA and part-time roles. 
- fraud-based-on-function-type outlines jobs based on the job function. Most fraudulent jobs were under the function NA, Administrative and Engineering.
- fraud-based-on-industry-type showcases industries with real and fraudulent job postings. Fraudulent jobs were mostly listed for industries like NA, Oil & Energy and Hospital & Health Care.  
- fraud-based-on-required-education-type highlights the required education needed for jobs. Fraudulent jobs usually required NA, high school or equivalent and bachelors degree.   
- fraud-based-on-required-experience-type underlines the required experience (Internship, Not Applicable, NA, Mid-Senior level, Associate, Entry level, Executive and Director) for jobs posted. Fraudulent jobs were mainly targeted for NA, Entry level and Mid-Senior level.
