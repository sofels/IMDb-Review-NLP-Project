# IMDb-Review-NLP-Project



### Objective
The objective of this project is to explore different machine learning models, feature sets and preprocessing techniques and to determine the best hyper parameters for models to predict the sentiments of movie reviews obtained by scraping the IMDb website. 

### Method
1000 movie reviews were collected from IMDb website through web scraping using the BeautifulSoup library. The sentiments of the reviews were manually labeled by each team member as positive, negative or neutral. The reviews were cleaned and tokenized. Lemmatization and Snowball stemming were utilized in preprocessing the tokens. To vectorize the tokens, four techniques were explored: Bag of Words, Term Frequency-Inverse Document Frequency (TF-IDF), bi-grams and a combination of these three vectorization techniques. Subsequently, machine learning classification models were investigated to find the optimal hyperparameter for accurate classification of the sentiments in the review. The models explored were: Logistic Regression, Naive Bayes and Random Forest Classifier. The best model was then used to classify user reviews and misclassified reviews were evaluated.

### Results
Our results revealed that the choice of preprocessing technique, lemmatization or snowball stemming, had little impact on the performance of the models. Across the three models explored, TF-IDF outperformed the other vectorization techniques, Bag of Words, bi-gram, and a combination of the three techniques. Overall, Naive Bayes model on TF-IDF vectors produced the best F1-score of 0.705. 

### Conclusion
In conclusion, this study highlights the importance of hyper parameter tuning, model selection and feature set selection with TF-IDF having a significantly higher validation score than the other feature sets. The study explored various preprocessing techniques, vectorization techniques, and machine learning models to determine the optimal approach for sentiment analysis of movie reviews. The results showed that the Naive Bayes was the best performing model with an F1-score of 0.705 and was also the least computationally expensive.  It was also discovered that a dataset of 1000 samples was likely a limiting factor in providing accurate results in that even small changes to the hyper parameters or the model seed could greatly influence the model accuracy.  Furthermore, the study found that the choice between stemming and lemmatization had little impact on the model's performance. Overall, this study provides a valuable starting point for further development into researching sentiment analysis for movie related text data.

### Contributors
- [Samuel Sofela](https://github.com/sofels)
- [Chris DiMattia](https://github.com/chd-vicis)
- [Sam Rainbow](https://github.com/SMRain10)
