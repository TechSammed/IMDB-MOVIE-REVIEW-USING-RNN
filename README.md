#Movie Review Sentiment Analysis (RNN-Based)

A deep learning project that predicts whether a movie review is Positive or Negative using a Recurrent Neural Network (RNN).
The model is trained on text reviews, processed through an NLP pipeline, and evaluated for real-world sentiment classification.

🚀 Features

✨ Text Preprocessing — tokenization, stopword removal, padding

🧠 RNN-based Model — captures sequential patterns in text

📊 Sentiment Classification — predicts Positive / Negative

📈 Performance Evaluation — accuracy, loss, confusion matrix

🗂️ Dataset — IMDB / custom movie review dataset

🧠 Tech Stack

Python, TensorFlow/Keras

RNN / LSTM layers

NumPy, Pandas, Matplotlib

Scikit-learn (train-test split, metrics)

📌 How It Works

Clean and preprocess text reviews

Convert text → sequences

Train RNN model on padded sequences

Predict sentiment on new reviews

Visualize training accuracy & loss

📝 Example Prediction

Input:
“The movie was absolutely amazing with great performances.”
Output:
Positive
