# Brainwave_Matrix_Intern
This project aims to build a Fake News Detection System using Machine Learning. The model classifies news articles as either Real or Fake based on their textual content. It leverages Natural Language Processing (NLP) techniques and various classification algorithms to improve accuracy.

# Features
Pre-trained machine learning model for text classification
Supports multiple datasets for training
Uses NLP techniques such as TF-IDF, Word Embeddings, and LSTMs
Simple user interface for testing news articles

# Installation
To set up this project, follow these steps:

# Clone the repository:
git clone https://github.com/yourusername/Fake_News_Detection.git
cd Fake_News_Detection

Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  
# On Windows use `venv\Scripts\activate`

# Install dependencies:
pip install -r requirements.txt

# Usage
To run the project, use the following command:
python app.py
This will start the web application where users can enter news articles and check if they are fake or real.

# Dataset
This project uses the Fake News Dataset from Kaggle, which contains real and fake news articles. You can download it from here and place it in the data/ directory.

# Model
The model is trained using:
Logistic Regression / Naive Bayes / LSTMs
TF-IDF vectorization
Word embeddings (Word2Vec, GloVe, BERT)
Trained models are stored in the models/ directory and can be loaded for prediction.

