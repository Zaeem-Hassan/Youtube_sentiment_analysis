🎯 YouTube Sentiment Analysis using Deep Learning
This project performs sentiment analysis on YouTube video comments using a fine-tuned transformer model. It includes data collection, preprocessing, model training, and a deployed Streamlit web app that provides real-time sentiment insights from any YouTube video.

📌 Features
🔴 YouTube Data Collection: Extract comments using the YouTube Data API.

🏷️ Custom Labeling: Manually labeled dataset into positive, negative, and neutral classes.

🤖 Model Training: Fine-tuned a transformer model (DistilBERT) on the labeled dataset.

🌐 Web App: Built with Streamlit to analyze sentiment of any YouTube video's comments.

📊 Visualizations: Pie chart and sentiment breakdown for quick insights.

🛠️ Tech Stack
Python

YouTube Data API

Hugging Face Transformers

PyTorch

Pandas, NumPy, Matplotlib

Streamlit

🚀 Installation

**Clone the Repository**

git clone https://github.com/Zaeem-Hassan/Youtube_sentiment_analysis.git
cd Youtube_sentiment_analysis

**Install Dependencies**

pip install -r requirements.txt

🧠 Model Info
Base model: distilbert-base-uncased

Fine-tuned on a small, manually labeled dataset of YouTube comments.

Output classes: Positive, Negative, Neutral.
