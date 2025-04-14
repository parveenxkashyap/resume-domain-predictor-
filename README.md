# Resume Domain Predictor

This is a Streamlit web application that predicts the domain or job category of a resume using Natural Language Processing and Machine Learning techniques.

## Features

- Upload resumes in PDF, DOCX, or TXT format
- Extract and clean resume text
- Predict the job category using a pre-trained SVC model

## How to Run Locally

1. Clone this repository
2. Install required packages:  
   `pip install -r requirements.txt`
3. Run the app:  
   `streamlit run app.py`

## Note

Model files (`clf.pkl`, `tfidf.pkl`, and `encoder.pkl`) are excluded via `.gitignore`. Ensure they are present in your local directory before running the app.
