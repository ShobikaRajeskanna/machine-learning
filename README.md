Dataset 1: Classification
The dataset, called FARS, is a collection of statistics of US road traffic accidents. The class label (target variable) is about the severity of the accident. It has 20 features and over 100K examples.

What is done with dataset 1:
EDA
Data normalisation
Split the data into training and test sets using cross-validation
Develop two machine learning pipelines for classifying the severity of the accident
Present the results for your pipeline using the most appropriate set of metrics.
Provide a short report on which approaches you used and which gave the best results. It would be good to consider why particular pipelines gave the best results.



Dataset 2: Regression
In this part of the coursework working at regession problem - predicting the growth rate of a bacteria. The provided dataset contains results from a set of experiments where we grew bacteria of different strains and under different conditions (CO2 availability, light, etc..) to compute a growth curve for the bacteria - represented by the variables 'a' and 'mu'. My job is to predict the results of the experiment - 'a' and 'mu' (these are the growth-rate parameters for the bacteria).

What is done with dataset 2:
EDA
Data normalisation
Split the data into train/test/validate
Develop two machine learning pipelines for predicting 'a' and 'mu'. This should include hyperparameter tuning. Note: This is not two pipelines one for 'a' one for 'mu'... but two pipelines for 'a', two for 'mu'...
Present the results for your models using the most appropriate set of metrics.
Provide a short report on which approaches you used and which gave the best results. It would be good to consider why particular models gave the best results.

Dataset 3: NLP
In this part of the coursework I wasworking at a dataset containing text from news articles. These are stored in a CSV file, however, as the news articles use commas I used a tab as the separator when reading in the file.
The file contains just one feature - the news story, one per line.

What is done with dataset 3:
EDA
Build a pipline which can transform the text into a format which can be handled by a machine learning model
Work out how many types of news articles are present in the dataset
Present the results for your work in the most appropriate means.
Provide a short report on which approaches you used and which gave the best results.

