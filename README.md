# Resume Classification Project

## Project Overview

This project focuses on automating the classification of resumes into specific job categories using natural language processing (NLP) and machine learning techniques. By processing the textual content of resumes and extracting relevant features, the model can predict the category to which a resume belongs, such as "Data Science," "HR," "Software Engineering," and more.

## Key Features

- **Data Preprocessing:** The resume text is cleaned using techniques like tokenization, stopword removal, and stemming/lemmatization to prepare it for classification.
- **Text Vectorization:** The cleaned text is transformed into numerical features using vectorization techniques such as TF-IDF.
- **Model Training:** Multiple machine learning models are trained, including Naive Bayes and k-Nearest Neighbors, to classify resumes based on extracted features.
- **Visualization:** The project visualizes category distributions and model performance through plots.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run

1. Clone the repository and navigate to the project directory.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Load the dataset and run the Jupyter Notebook (`resume-classification.ipynb`) to preprocess the data and train the models.

## Results

The project achieves reliable classification of resumes into various categories, helping automate the recruitment process by quickly filtering and categorizing candidate profiles.
