# Fake-news-detection
### Fake News Detection

#### Description:

This project aims to detect fake news using machine learning techniques, specifically employing the Passive Aggressive Classifier on a dataset containing news articles. The dataset consists of news articles labeled as either 'FAKE' or 'REAL'. The detection process involves text preprocessing, feature extraction using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization, and training the classifier to predict the authenticity of news articles.

#### Key Components:

1. **Dataset:**
   - The dataset used in this project contains news articles with corresponding labels indicating whether they are real or fake.

2. **Preprocessing:**
   - Text data undergoes preprocessing, including removing stop words and other noise, to prepare it for feature extraction.

3. **Feature Extraction:**
   - TF-IDF vectorization is employed to convert the text data into numerical features, considering the importance of terms in the documents.

4. **Model Training:**
   - The Passive Aggressive Classifier, a popular algorithm for online learning and classification tasks, is utilized to train the model on the TF-IDF transformed data.

5. **Evaluation:**
   - The model's accuracy is evaluated using the test dataset, and a confusion matrix is generated to assess the classifier's performance in distinguishing between fake and real news articles.

#### Acknowledgments:

- This project utilizes the scikit-learn library for machine learning functionalities.
- The dataset used for training and testing is sourced from  Kaggle.
