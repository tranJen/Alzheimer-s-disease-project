# Machine Learning Approaches for Alzheimer’s Disease data analysis

Data used in our projects: extracted from National Alzheimer’s Coordinating Center (NACC) data

[Orginial Data can be requested here!](https://naccdata.org) 

- 13689 patients’ data collected since 2005 during standardized annual evaluations conducted at the NIA-funded Alzheimer’s Disease Research Centers (ADRCs) across the country.
- 22 features selected based on literature review and easiness-to-understand for normal people

## Abstract

Alzheimer's disease (AD) is a neurodegenerative disorder characterized by cognitive decline.
Previous researches have been trying to apply machine learning for predicting the happening of
this disease, but the features are often complicated and difficult for normal people to interpret.
This study addresses this challenge by employing unsupervised machine learning techniques to
analyze a dataset from the National Alzheimer’s Coordinating Center (NACC). The dataset
includes various easy-to-understand features related to demographics, lifestyle, health conditions,
cognitive assessments, and functional activities of individuals with AD. Using unsupervised
learning, the study identifies patterns and relationships within the dataset. Subsequently,
supervised learning algorithms are utilized to predict the Clinical Dementia Rating (CDR) score,
a crucial measure of cognitive decline, from the extracted features. The results of this analysis aim to enhance our understanding of AD progression and support early diagnosis and
intervention strategies.


## Models 

#### K-mean clustering 
With given features, the data was clustered in 2 groups, then we analyzed the group based on the features to identify which group is prone to be identifed as "having AD".
#### Supervised learning models
- Linear Regeression
- LASSO Regression
- Support Vector Regressor
- Random Forest Regressor

#### _For details and outcome summary, please navigate "AD poster.pdf" file_

