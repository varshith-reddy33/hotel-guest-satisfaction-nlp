# Hotel Guest Satisfaction Analysis using NLP

An NLP and machine learning project that analyses large-scale hotel reviews and classifies customer reviews as **Satisfied** or **Dissatisfied**.

## Project Overview

This project analyses more than **515,000 hotel reviews** to identify customer satisfaction patterns and build a machine learning model for review classification.

The project focuses on preparing large-scale text data, extracting meaningful features using TF-IDF, comparing classification models, and analysing the resulting predictions.

## Objectives

* Explore patterns in hotel guest reviews
* Clean and prepare large-scale review text data
* Convert text into numerical features using TF-IDF
* Compare machine learning classification models
* Identify important words and phrases associated with customer satisfaction
* Evaluate the final model using classification metrics

## Dataset

The project uses a hotel review dataset containing **515K+ review records**.

The dataset includes information related to hotel reviews and customer experiences.

The original dataset is **not included in this repository** because of its size.

## Methodology

The project follows these main steps:

1. Data loading and initial inspection
2. Data cleaning and preprocessing
3. Handling duplicates and conflicting reviews
4. Creation of the satisfaction target
5. Exploratory data analysis
6. Text preprocessing
7. TF-IDF feature extraction
8. Unigram and bigram feature comparison
9. Model training and comparison
10. Final model evaluation
11. Feature interpretation and error analysis

## Machine Learning Models

The project compares:

* Logistic Regression
* Linear Support Vector Classification (LinearSVC)

TF-IDF features were evaluated using both unigram and bigram representations.

## Results

The final Logistic Regression model using TF-IDF bigram features achieved approximately:

| Metric                | Result |
| --------------------- | -----: |
| Accuracy              |  81.1% |
| Recall – Dissatisfied |  81.1% |

The model was evaluated using classification metrics and a confusion matrix.

The analysis also examined important words and phrases associated with positive and negative customer experiences.

## Key Insights

The project demonstrates how large-scale customer review data can be transformed into structured information for analysis.

The text features provide insight into recurring themes associated with customer satisfaction and dissatisfaction, which can help identify areas of the hotel experience that may require attention.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Natural Language Processing (NLP)
* TF-IDF
* Jupyter Notebook

## Repository Structure

```text
hotel-guest-satisfaction-nlp/
│
├── Hotel_Guest_Satisfaction_NLP.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── data/
    └── README.md
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/hotel-guest-satisfaction-nlp.git
cd hotel-guest-satisfaction-nlp
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Obtain the dataset

Download the original hotel review dataset separately and place it in your local environment.

The dataset is not included in this repository because of its size.

### 4. Update the dataset path

Open:

`Hotel_Guest_Satisfaction_NLP.ipynb`

and update the dataset path used by the notebook.

### 5. Run the notebook

```bash
jupyter notebook
```

Open `Hotel_Guest_Satisfaction_NLP.ipynb` and run the cells from beginning to end.

