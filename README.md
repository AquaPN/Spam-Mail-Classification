📧 Spam Email Classification using Machine Learning/n
This project builds a spam email classifier using TF-IDF vectorization and Multinomial Naïve Bayes (NB). It processes raw email text, converts it into numerical features, and trains a model to distinguish between spam and non-spam emails.

🚀 Features
✅ Preprocessing: Converts raw text into numerical form using TF-IDF
✅ Machine Learning Model: Uses Multinomial Naïve Bayes for classification
✅ Handling Missing Data: Automatically fills or removes NaN values in labels
✅ Training & Testing: Splits the dataset into train (80%) and test (20%)
✅ Accuracy Evaluation: Measures model performance on unseen data

🛠️ Technologies Used
Python
Scikit-Learn (ML model, TF-IDF, preprocessing)
Pandas (Data handling)
NumPy (Efficient array operations)
📂 Dataset
The dataset should contain two columns:
text → Email content
label → Classification (Spam or Not Spam)
Ensure the dataset is clean and free of missing values.

📊 Results
The model achieves high accuracy in detecting spam emails. You can further improve it by tuning hyperparameters or using advanced NLP techniques like deep learning.

🔗 Future Enhancements
🔹 Implement deep learning models (LSTMs, Transformers)
🔹 Use pre-trained embeddings (Word2Vec, BERT)
🔹 Deploy as a web API for real-time email classification
