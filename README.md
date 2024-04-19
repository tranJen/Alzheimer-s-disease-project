# Machine Learning Approaches for Alzheimer’s Disease data analysis

![image](https://github.com/tranJen/Alzheimer-s-disease-project/assets/143001830/a0e21846-85cd-49b2-ace8-8765a18a21d2)

Data used in our projects: extracted from National Alzheimer’s Coordinating Center (NACC) data

[Orginial Data can be requested here!](https://naccdata.org) 

- 13689 patients’ data collected since 2005 during standardized annual evaluations conducted at the NIA-funded Alzheimer’s Disease Research Centers (ADRCs) across the country.
- 22 features selected based on literature review and easiness-to-understand for normal people

## Motivation

Alzheimer's disease is one of the most challenging neurodegenerative disorders facing society today. It is a progressive disease that affects memory,
thinking, behavior, and eventually leads to loss of independence and quality of life for millions worldwide. As the global population ages, 
the prevalence of Alzheimer's disease is expected to rise significantly, resulting in a growing public health concern and increasing healthcare costs. 
Despite the extensive research efforts over the years, there is currently no known cure, and existing treatments primarily focus on alleviating symptoms rather than addressing 
the underlying causes of the disease.This study addresses this challenge by employing unsupervised machine learning techniques to
analyze a dataset from the National Alzheimer’s Coordinating Center (NACC). The dataset
includes various easy-to-understand features related to demographics, lifestyle, health conditions,
cognitive assessments, and functional activities of individuals with AD. Using unsupervised
learning, the study identifies patterns and relationships within the dataset. Subsequently,
supervised learning algorithms are utilized to predict the Clinical Dementia Rating (CDR) score,
a crucial measure of cognitive decline, from the extracted features. The results of this analysis aim to enhance our understanding of AD progression and support early diagnosis and
intervention strategies.

## Models 

#### Data dictionary
This is the meaning of the 22 features that we selected for this project.
CDRSUM: Clinical Dementia Rating
DECIN: Decline in memory
MOSLOW: Slowness in motion
MEMORY: Memory impairment
SPEECH: Difficulties with speech
BILLS: Difficulties with bills
TRAVEL: Difficulties with travel
MOFALLS: Experience more falls
MOTREM: Experience more tremor
NACCAGE: Age
NACCBMI: BMI (Body Mass Index)
TOBAC30: Smoked during the last 30 days
TOBAC100: Smoked more than 100 cigarrets throughout the participant's life
PACKSPER: Number of cigarrets pack per month
SMOKYRS: The number of smoking years
QUITSMOK: The age that a participant quit smoking
ALCOHOL: Alcohol abuse history
DIABETES: Diabetes history
HYPERTEN: Hypertension history
CVHATT: heart attack/cardiac arrest history
SEX: sex

#### K-means clustering 
Since the original data doesn't have any label for Alzheimer, the most appropriate approach was touse unsupervised learning. And the selected method is K-means clustering. With given features, the data was clustered in 2 groups, then we analyzed the group based on the features to identify which group is generally healthier.

_For details, please navigate "AD project.ipynb" and "analyze-after-clustering.ipynb" file_
#### Supervised learning models
- Linear Regeression
- LASSO Regression
- Support Vector Regressor
- Random Forest Regressor
  
_For details, please navigate "Supervised learning.ipynb" file_

### _For details and outcome summary, please navigate "AD poster.pdf" file_

