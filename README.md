📰 Fake News Detector
Detect whether a news article is real or fake using Machine Learning



📌 Live Demo
👉 Click here to try it on Hugging Face Spaces
(https://huggingface.co/spaces/aarzuuc/fake-news-detector)

💡 What It Does
This web app uses a logistic regression model trained on real-world news headlines to determine whether a given news article is real or fake.

🔍 Dataset
Fake and Real news articles from Kaggle

Cleaned, preprocessed, and labeled:

0 = Fake

1 = Real

⚙️ Tech Stack
Tool	Use
Python	Core programming language
Scikit-learn	ML model training & TF-IDF vectorizer
NLTK	Text preprocessing (lemmatization etc)
Gradio	Web app / User Interface
Hugging Face	Model hosting

🛠 How It Works
Preprocesses text: lowercasing, tokenizing, lemmatizing, removing stopwords

Converts text into numeric vectors (TF-IDF)

Predicts with a trained LogisticRegression model

Displays result: 🔴 FAKE or 🟢 REAL


🧠 Want to Contribute?
Pull requests and forks welcome. Drop ideas, report issues, or help improve the model!

✨ Credits
Dataset: Kaggle - Fake and Real News Dataset

UI: Gradio

Hosting: Hugging Face Spaces

