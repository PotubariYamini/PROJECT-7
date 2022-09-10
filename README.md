Financial-SENTIMENTAL ANALYSIS

![image](https://user-images.githubusercontent.com/111189874/189470185-f84a719f-83fc-4591-9880-21efb7063366.png)


1. About dataset:
* The following data is intended for advancing financial sentiment analysis research. It's two datasets (FiQA, Financial PhraseBank) combined into one easy-to-use CSV file. It provides financial sentences with sentiment labels.

2. Requirements:
* python 
* jupyter notebook
* numpy
* pandas 
* sklearn library
* models like: Logistic Regression, Random forest, AdaBoostclassifier
* matplotlib

3. Data preprocessing:
* load the data by using pandas
* we clean the data. first we check the null values.
* then we start the preprocessing 
* wordcloud to get different views: considering each sentiment, pre and post processing

4. visualization of the data:
by using seaborn :

![image](https://user-images.githubusercontent.com/111189874/189470301-fdec384f-7c2e-4cd0-8e63-d01260913d9b.png)



4. Building the model:
*  vectorizing the sentences with CountVectorizer and TfidfVectorizer (Tfidf)
* trying different approaches for this unbalanced problem: with and without data augmentation
*  training different models within the 2 different vectorizations:  MultinomialNB, LogisticRegression, RandomForestClassifier, SVC
*  plotting accuracy's and confusion matrix (for test set)
*  resume and present the results

5. we train model and test the accuracy of the model.
