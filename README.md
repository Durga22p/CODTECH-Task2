# Movie Reviews Sentiment Analysis using machine learning
Implemented text analysis using machine learning models to classify movie review sentiments as positive or negative. Built using Python 3.6.1.

1. Tuned CountVectorizer (1_gram) to get appropriate features/tokens and then transformed to obtain input variable (document term matrix).
2. Splitted training test with test size of 20%
3. Used the following models to train on training data.
    - Naive Bayes
    - Logistic Regression
    - SVM (Support Vector Machine)
    - KNN (K Nearest Neighbors)
4. Tested models on test data and calculated accuracy of predictions
5. The results were as follows:
    - Naive Bayes: 98.9161849711%
    - Logistic Regression: 99.3497109827%
    - SVM: 99.0606936416%
    - KNN: 98.6994219653%
6. Analysed further by observing confusion matrix
7. Used Naive Bayes model to observe the number of tokens (words) and the positivity/negativity associated with that word.
8. Implemented searching of selected words in the pandas dataframe to analyse specific words in the feature sets
9. Used the most accurate model (Logistic Regression) to train on the entire dataset. df
10. Took custom review inputs and predicted Positive/Negative review.


![Screenshot (116)](https://github.com/user-attachments/assets/59040fa9-4b66-4bd4-8839-3b065576a925)


![Screenshot (117)](https://github.com/user-attachments/assets/a6c947d8-de1c-43ce-bda3-6238157273eb)


![Screenshot (118)](https://github.com/user-attachments/assets/779921d0-c127-4163-93bc-0f043de7ca3f)


![Screenshot (119)](https://github.com/user-attachments/assets/d01f2ba4-ba16-4d11-8434-c1013e4e6ea3)


![Screenshot (120)](https://github.com/user-attachments/assets/79f472c5-7168-4765-ac9b-8cc406e1ca8c)


![Screenshot (121)](https://github.com/user-attachments/assets/1ec7cb9a-f1ac-49af-8a1e-41d2c9ae533e)



