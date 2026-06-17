# Assignment-2C-IMDB-Movie-Review-Sentiment-Analysis
# 🎬 IMDB Movie Review Sentiment Analysis

A Machine Learning project that predicts whether a movie review is **Positive 😊** or **Negative 😡** using **Natural Language Processing (NLP)** and **Logistic Regression**.

This project uses the popular **IMDB Dataset** from Kaggle and applies **TF-IDF Vectorization** to convert text into numerical features before training the model.

---

## 📌 Features

* ✅ Loads and processes the IMDB Kaggle dataset
* ✅ Cleans HTML tags from reviews
* ✅ Converts text labels into binary format
* ✅ Uses **TF-IDF Vectorization** for text processing
* ✅ Trains a **Logistic Regression** model
* ✅ Evaluates model performance using:

  * Accuracy Score
  * Classification Report
  * Confusion Matrix
* ✅ Visualizes results using **Seaborn Heatmap**
* ✅ Includes an **interactive sentiment predictor**

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

Dataset used: **IMDB Movie Reviews Dataset**

You can download it from Kaggle:

[IMDB Dataset on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?utm_source=chatgpt.com)

After downloading, place the file:

```bash
IMDB Dataset.csv
```

in the same folder as the Python script.

---

## 📁 Project Structure

```bash
📦 imdb-sentiment-analysis
 ┣ 📜 sentiment_analysis.py
 ┣ 📜 IMDB Dataset.csv
 ┣ 📜 README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/tanishq-jain124/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
```

### 2️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ How to Run

Run the Python script:

```bash
python sentiment_analysis.py
```

---

## 🔄 Workflow

### 1. Data Loading

* Loads the IMDB dataset from CSV file
* Samples 10,000 reviews for faster training

### 2. Data Preprocessing

* Removes HTML tags
* Converts sentiment labels:

  * Positive → 1
  * Negative → 0

### 3. Text Vectorization

* Uses **TF-IDF Vectorizer**
* Removes English stopwords
* Keeps top 10,000 important words

### 4. Model Training

* Trains a **Logistic Regression** classifier

### 5. Evaluation

* Calculates:

  * Accuracy
  * Precision
  * Recall
  * F1-score

### 6. Visualization

* Displays a **Confusion Matrix Heatmap**

### 7. User Prediction

* Allows users to input custom movie reviews
* Predicts sentiment with confidence score

---

## 📊 Sample Output

```bash
=============================================
--- MODEL PERFORMANCE EVALUATION ---
=============================================

Accuracy Score: 89.45%

Detailed Classification Report:

              precision    recall  f1-score   support

Negative       0.89       0.90      0.89      1000
Positive       0.90       0.89      0.89      1000
```

---

## 📈 Confusion Matrix

The project visualizes prediction performance using a heatmap generated with Seaborn.

![Image](https://images.openai.com/static-rsc-4/HT6ViBF6MuRD5CnhhM80vNyf1_oU8UhBPhqPZr7Dv-u6CdhaFiQHAO_Vw_RfrRDwunPJI41K7H1QkwmxEpggOT4HtLylZXG8Cwrj3bioK9INaPfnZcKhXPKKbbif9_6lsHwdyT4RmoPgz07Mgks2QFU5b-s6KyrOKDjKyJxVUZjZsV9fFTRZMtRyrhND7aFT?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/hyOmXlmkU_u_qtsLjSqs6PSm62FX3zPDVX3Pv0EahAChFNMTN_kBXQR7SgfHPuRzO9M1sVXl1ZVK9Em5kY7doktdBFbpSj5bVoSibqGi28LTA36M9ZHnxy1KBFf103SN24VfgHWrAPH2DNpqSMdwCCHN7YYO6RSS88SaCvTm36-cLNR1bGq1nn6Exx-iD1W8?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/JbyhkPTPys_t1O3xwLEvWw4AsFpr43qk2E9rtrE9zYF14-rmGVrVcRw2FjgztzCz91Dr1nynJEpD8IJWGeqp0pHcD3NOKn4g3hvpoPmv3GvrSyQNvNX-Mn9IbVok59t3KERr0VEaIUr515NIQAIBW8b0eOfHWNAusZ6lNQo6FfCJU4cKFLFx9uYUmQt_l30Q?purpose=fullsize)

---

## 🧠 Machine Learning Concepts Used

* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Logistic Regression
* Text Classification
* Model Evaluation Metrics

---

## 🚀 Future Improvements

* Add Deep Learning models (LSTM / BERT)
* Create a Web App using Flask or Streamlit
* Train on full 50K dataset
* Save and load trained model using Pickle
* Deploy on cloud platforms

---

## 📜 License

This project is open-source **.

---

## 👨‍💻 Author

Developed by **Tanishq**

If you like this project, give it a ⭐ on GitHub!
