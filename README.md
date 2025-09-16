The workflow of the project is as follows: <br>

1. News articles labelled as real/fake news with authors name is downloaded from kaggale consisting of 72,124 news articles. <br>
2. The data is pre-processed to deal with a mix of text and numerical data (strings). Here, the Tf-idf Vectorizer is used to convert text to feature vectors (numbers) <br>
3. The data is then split into train and test data. <br>
4. A logistic regression model is prepared. 1 is assigned for real news and 0 for fake news. <br>
5. After training the logistic regression model, we feed new data and check whether the news is real or fake, achieving a 94.78% test accuracy.
