# JD Analyzer & Skill Gap Detector

## Project Overview
JD Analyzer & Skill Gap Detector is a machine-learning-based application that analyzes job descriptions, predicts job categories, and identifies skill gaps between job requirements and candidate skills.

## Objectives
- Classify job descriptions into different job categories.
- Identify required and missing skills.
- Calculate candidate skill-match percentage.
- Provide an interactive user interface.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF
- Logistic Regression
- Gradio
- Pickle

## Dataset
The project uses a self-generated CSV dataset containing 600 job-description records across six categories.

Dataset file: `jd_analyzer_dataset.csv`

## Machine Learning Algorithm
Logistic Regression is used for job-category classification, with TF-IDF for text feature extraction.

## Main Features
1. Job description analysis.
2. Job category prediction.
3. Prediction confidence.
4. Matched skills identification.
5. Missing skills identification.
6. Skill-match percentage.

## How to Run

1. Clone or download this repository.
2. Install dependencies:
   `pip install -r requirements.txt`
3. Run the application:
   `python app.py`

## Project Type
Academic Mini Project
