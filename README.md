# Assignment 4 - Final Project

### An Analysis of Mental Health and Mental Health Variation Between Countries  

After assessing and manipulating the "survey.csv" data source - and more specifically the variables "Country", "seek_help", and "treatment" - the answer to the question "how does the frequency of mental health illness and attitudes towards mental health vary by geographic location" became clear. First, it's important to offer insight into what each of the variables used mean; the following descriptions were provided via the URL https://www.kaggle.com/osmi/mental-health-in-tech-survey (the same website the class was instructed to source the dataset from):

1. "Country": The respondent country
2. "seek_help": Does your employer provide resources to learn more about mental health issues and how to seek help?
3. "treatment": Have you sought treatment for a mental health condition? Important note: the "treatment" variable was only used in the following analysis to count responses of the "seek_help" variable. 

First, it's important to highlight that discovering and comparing the frequency of mental health illness from country to country on an efficient scale was impossible given the dataset. The United States had the highest frequency of data entries, and therefore the most cases of mental health illness (under the assumption that every single data entry was someone who was suffering from mental health illness); however, a more effective metric would be to discover the "Mental Health Illness Level Per Capita" - a metric that simply cannot be discovered with this dataset. 

With that being said, the dataset still enables a comparison of attitudes towards mental health illness depending on geographical region. In this analysis, the "seek_help" variable was assessed to discover the individuals that were emboldened and able to seek help for their mental health illness (indicating a positive culture and attitudes surrounding mental health illness) and those individuals that work for organization that don't offer - or are unsure if their organization offers - mental health services (indicating a negative culture and attitudes surrounding mental health illness).

Output was produced for countries where individuals knew that their organization was able and willing to provide help for mental health illness, and corresponding data on those individuals that responded "No" or "Don't know" was also recorded. The negative data was combined (i.e. the cumulation of the "No" and "Don't know" responses), and graphics comparing the countries' positive responses to the negative responses were created. Please note: all countries that only had negative responses were dropped from the analysis. 

### Conclusion of Analysis

The results of the analysis were interesting. Initially, it appeared that the United States and the United Kingdom both provided the best culture surrounding mental health illness (they both had the highest frequencies of "Yes" responses); however, upon comparing the two graphics and data outputs, it's clear that other nations are taking better approaches. The United States had good and positive culture according to only 25.17% of respondents (189/751 = "Yes" responses/ total responses), and the U.K. had a dismal 14.05% rate of positive response (26/185); whereas nations such as The Bahamas had a perfect score (1/1) and Australia had the second best rate of 38.09% (8/21). In the future, these "First-World" nations - such as the United States, the United Kingdom, Canada and Germany must look towards Australia and The Bahamas to discover how they've improved their ratios. As well, further datasets should be assessed to ensure that these values are typical and not high/low by chance. 
 