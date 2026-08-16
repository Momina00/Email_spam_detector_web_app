![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![NLP](https://img.shields.io/badge/NLP-Text%20Processing-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# Email Spam Detector


A Machine Learning project that detects whether an email/message is Spam or Not Spam using Natural Language Processing (NLP).

## Features
- Detects spam messages instantly
- Text preprocessing using NLP
- Trained ML model for prediction
- Simple and user-friendly interface
- Real-time message testing

## Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK
- Streamlit
- Docker
- GitHub Actions

## How It Works
1. User enters an email/message
2. Text is cleaned and processed
3. ML model analyzes the text
4. Prediction is displayed as:
   - Spam
   - Not Spam

## Machine Learning Concepts Used
- Natural Language Processing (NLP)
- Tokenization
- Stopword Removajjlkll
- TF-IDF Vectorization
- Naive Bayes

## DevOps Implementation
- Created a Dockerfile to containerize the Streamlit application.
- Configured GitHub Actions to automatically build the Docker image on code changes.
- Used Git and GitHub for version control and project management.

## Dataset
Used a spam email dataset containing labeled spam and ham (non-spam) messages for training and testing.

## Live Demo
link: https://emailspamdetectorwebapp-qfsftl742sanceswgdxfzj.streamlit.app/


## Installation

```bash
pip install -r requirements.txt
python app.py
```

## Docker

> Build the image:
```bash
docker build -t spam-email-detector .
```
> Run the container:
```bash
docker run -p 8501:8501 spam-email-detector
```
