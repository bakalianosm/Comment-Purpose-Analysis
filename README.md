# Comment Purpose Analysis

This is a project that we had to implement in the course of **Data Mining** this semester ( 2019 - 2020 ) .
The professor gave us the data that we had to use and I just made the Notebook that represents my work .


## Contents:
* Data Folder 
  * [test_imperium_labels.csv](#test-imperium-labels)
  * [train.csv](#train)
* [Jupyter Notebook File](#Jupyter-Notebook)


### test imperium labels 
This is a **csv** file with pre-labeled comments and it is used for testing.
This file has a completed column named insult that takes values either **0 (neutral)** either **1 (insulting)** and represents the actual purpose of the comment . 

### train
This is a csv file that is used to train the algorithms.It is the same as the test_imperium_labels.csv but it has incompleted the **insult** row

### Jupyter Notebook 
List of what I had to do :
1. Text Preprocessing (remove punctuation, links etc.)
2. Use Naive-Bayes Classification Algorithm
3. Improve Naive-Bayes using Laplace Smoothing , lemmatization & remove stopwords 
4. Make a new dataframe using Part Of Speech & TF-IDF Based Characteristics
5. Use SVM for POS Tagged df
6. Use Random Forest for POS Tagged df
