# 🛒 Amazon Product Review Sentiment Analysis

This project is a Machine Learning application that analyzes Amazon product reviews and predicts the sentiment as either **Positive** or **Negative**. It uses a trained **Logistic Regression** model and provides a user-friendly web interface using **Streamlit**.

## 🚀 Live Demo
### [👉 Click Here to Use the App](https://amazon-review-w.streamlit.app)

---

## 🛠 Tech Stack & Libraries
- **Python** (Core Language)
- **Streamlit** (Web Interface)
- **Scikit-Learn** (Machine Learning Model)
- **NLTK** (Natural Language Processing)
- **Pandas** (Data Manipulation)

---

## 📂 Project Structure
Here is an overview of the files in this repository:

| File Name | Description |
| :--- | :--- |
| **`streamlit_frontend.py`** | The main Streamlit application file that runs the web interface. |
| **`amazon_review.ipynb`** | Jupyter Notebook used for Data Cleaning, EDA, and Model Training. |
| **`sentiment_pipeline.pkl`** | The trained Machine Learning model saved using Joblib. |
| **`requirements.txt`** | List of all Python libraries required to run this project. |
| **`amazon.csv`** | The dataset used for training the model. |

---

## ⚙️ How to Run Locally
If you want to run this project on your own computer, follow these steps:

**1. Clone the Repository**
bash
git clone git@github.com:mehedi-hasan00/Amazon-Sentiment-Analysis-Project.git
cd Amazon-Sentiment-Analysis-Project
**2. Install Dependencies**
pip install -r requirements.txt
**3. Run the App**
streamlit run streamlit_frontend.py

## 📊 Model Details
- **Algorithm:** Logistic Regression
- **Vectorization:** TF-IDF / CountVectorizer
- **Preprocessing:** Stopwords removal, Lemmatization, and Punctuation removal.

---

### 👨‍💻 Developed by **Mehedi Hasan**
```

