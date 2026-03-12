#  Movie Genre Classification using TF-IDF and Logistic Regression

##  Project Overview

This project builds a **Machine Learning model that predicts the genre of a movie based on its plot summary**.

The model uses **Natural Language Processing (NLP)** techniques to convert movie descriptions into numerical features using **TF-IDF (Term Frequency–Inverse Document Frequency)** and then classifies them using a **Logistic Regression model**.

This project demonstrates how **text classification can be applied to real-world datasets**.

---

## Dataset

The dataset used in this project is publicly available.

Download it from:
https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

Files required to run the project:

* `train_data.txt`
* `test_data.txt`
* `test_data_solution.txt`

After downloading the dataset, place these files in the **same directory as the notebook** before running the code.

Dataset format:

```
ID ::: TITLE ::: GENRE ::: DESCRIPTION
```

Example:

```
1 ::: Oscar et la dame rose (2009) ::: drama ::: Listening in to a conversation...
```

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Logistic Regression

---

## Machine Learning Pipeline

The workflow of this project:

```
Movie Dataset
      ↓
Text Preprocessing
      ↓
TF-IDF Feature Extraction
      ↓
Logistic Regression Model
      ↓
Genre Prediction
```

Steps performed:

1. Load movie dataset
2. Extract movie descriptions
3. Convert text to numerical features using **TF-IDF**
4. Train a **Logistic Regression classifier**
5. Evaluate the model
6. Predict genres for unseen movies

---

##  Model Performance

Validation Accuracy:58%


The dataset contains **multiple genres and significant class imbalance**, where some genres appear far more frequently than others. This makes the classification problem more challenging.

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* F1-Score

Example Predictions:

| Movie Title          | Predicted Genre |
| -------------------- | --------------- |
| Edgar's Lunch        | Comedy          |
| La guerra de papá    | Drama           |
| Off the Beaten Track | Documentary     |
| Meu Amigo Hindu      | Drama           |

Predictions are saved in:

```
predicted_genres.csv
```

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/Navya2516/movie-genre-classification.git
```

2. Install dependencies

```
pip install pandas scikit-learn
```

3. Download the dataset from the link above.

4. Place the dataset files in the project folder.

5. Run the notebook:

```
movie_genre_prediction.ipynb
```

---

## Project Structure

```
movie-genre-classification
│
├── movie_genre_prediction.ipynb
├── predicted_genres.csv
├── Movie Genre.mp4
└── README.md
```

---

##  Future Improvements

Possible improvements to the project:

* Use **Word Embeddings (Word2Vec, GloVe)**
* Apply **Deep Learning models (LSTM, BERT)**
* Handle class imbalance using advanced techniques
* Hyperparameter tuning
* Compare with additional models (SVM, Random Forest)

---

##  Learning Outcomes

This project demonstrates:

* Natural Language Processing techniques
* Text feature extraction using TF-IDF
* Multi-class classification
* Logistic Regression for text classification
* Model evaluation and predictions

---

##  Author

**Navya Saravanan**
AIML Student

---

##  Contact
LinkedIn: https://www.linkedin.com/in/navya-saravanan-8aa481311

