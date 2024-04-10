
# SC1015 Mini-Project : Exploration of Contributing Factors of Flight Delay

Nanyang Technological University

Data Science and Artificial Intelligence

Group 8 (FDAD) 2024



## Authors

- Devlin Waluja [@devlinwaluja](https://www.github.com/devlinwaluja)
- Jun Long Lim [@mrbeastok](https://www.github.com/mrbeastok)


## Descripton

This GitHub repository contains all the .ipnyb files, videos and more. Due to the sheer size of the dataset used, you may download the datset locally through this kaggle link: https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022

We have chosen to use the 2018 dataset as the data post 2019 is affected by the COVID-19 Pandemic which may yield abnormal reults.

## Libraries / Concepts Implemented
1.) Pandas
- DataFrame handling

2.) NumPy
- Data handling

3.) Matplotlib
- Graphical representations

4.) Wordcloud
- Visual representations

5.) Scikitlearn
- Stratified Sampling
- Naïve Bayes Classification

6.) KModes
- KModes clustering

7.) Seaborn
- Default Graphics
## Problem Definition
- What are the main contributing factors of a delayed domestic flight in the United States in 2018?
- Are we able to predict a flight's delay status based on certain factors?

## Contents
(Listed in order):

1.) [Data Extraction and Cleaning](https://github.com/devlinwaluja/SC1015-Group-8/blob/8217101944be5fb4bd147f6f41c7fd4065b49aa3/Data%20Extraction%20and%20Cleaning.ipynb)
- Extraction of dataset
- Removal of anomalous data
- Identification of predictors
- Identifiction of Response Variable
- Isolation of predictors and response variable
- Integration of 'Cancelled' and 'DepartureDelayGroups'

2.) [Data Visualization](https://github.com/devlinwaluja/SC1015-Group-8/blob/8217101944be5fb4bd147f6f41c7fd4065b49aa3/Data%20Visualization.ipynb)
- Representation of selective predictors with bar charts
- Conversion of Scheduled Departure Time to categorical for data visualization
- TreeMap visualization for remaining predictors
- Representation of response variable using bar chart

3.) [Data Sampling and Machine Learning](https://github.com/devlinwaluja/SC1015-Group-8/blob/8217101944be5fb4bd147f6f41c7fd4065b49aa3/Data%20Sampling%20and%20Machine%20Learning.ipynb)
- Stratified Sampling of data
- Categorical Naïve Bayes Classification Algorithm
- Analysis of Naïve Bayes Classification Algorithm results
- KModes Clustering 
- Analysis of KModes clustering results
- Conclusion
## Learning points / Conclusion
### Key Learning points
- Handling large datasets
- Implementation of Statified Sampling and its benefits when dealing with categorical data
- Categorical Naïve Bayes Classification Algorithm
- KModes Clustering
- Familiarization with GitHub


### Conclusion
In this mini-project, we initially sought to explore the contributing factors to one's flight status. Through the use of Naïve Bayes classification and Kmodes Clustering, we have come to the conclusion that there is no predictor (both individually or as a collective) that performs as a satisfactory predictor of flight status.

This leads us to conclude that there are more external factors that have a big role in flight delay, for example, sudden onset of meteoritical conditions such as intense downpour or high crosswinds, or maybe even political issues resulting in strikes. All of which are out of the control of the customer flying.
## Acknowledgements

- https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022
- https://vitalflux.com/categorical-data-visualization-concepts-examples/
- https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.CategoricalNB.html
- https://visualstudiomagazine.com/articles/2023/03/01/naive-bayes-scikit.aspx
- https://www.geeksforgeeks.org/stratified-sampling-in-pandas/
- https://proclusacademy.com/blog/stratified_sampling_pandas/
- https://pypi.org/project/kmodes/
- https://www.analyticsvidhya.com/blog/2021/06/kmodes-clustering-algorithm-for-categorical-data/
- https://www.geeksforgeeks.org/k-mode-clustering-in-python/
- https://medium.com/@reddyyashu20/k-means-kmodes-and-k-prototype-76537d84a669

