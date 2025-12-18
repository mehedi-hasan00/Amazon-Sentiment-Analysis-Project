# 🛒 Amazon Product Review Sentiment Analysis

This project is a **Machine Learning application** that analyzes Amazon product reviews and predicts the sentiment as either **Positive** or **Negative**. It uses a trained **Logistic Regression** model and provides a user-friendly web interface using **Streamlit**.

---

## 🚀 Live Demo

[👉 Click Here to Use the App](https://amazon-review-w.streamlit.app)

---

## 🛠 Tech Stack & Libraries

- **Python** – Core Language  
- **Streamlit** – Web Interface  
- **Scikit-Learn** – Machine Learning Model  
- **NLTK** – Natural Language Processing  
- **Pandas** – Data Manipulation  

---

## 📂 Project Structure

| File Name | Description |
|-----------|-------------|
| `streamlit_frontend.py` | The main Streamlit app to run the web interface. |
| `amazon_review.ipynb` | Jupyter Notebook for Data Cleaning, EDA, and Model Training. |
| `sentiment_pipeline.pkl` | Trained Logistic Regression model saved with Joblib. |
| `requirements.txt` | List of Python dependencies to run the project. |
| `amazon.csv` | Dataset used for training the model. |

---

## ⚙️ How to Run Locally

1. **Clone the repository**

```bash
git clone git@github.com:mehedi-hasan00/Amazon-Sentiment-Analysis-Project.git
cd Amazon-Sentiment-Analysis-Project
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Streamlit app**

```bash
streamlit run streamlit_frontend.py
```

---

## 📊 Model Details

- **Algorithm:** Logistic Regression  
- **Vectorization:** TF-IDF / CountVectorizer  
- **Preprocessing:** Stopwords removal, Lemmatization, and Punctuation removal  

---

### 👨‍💻 Developed by **Mehedi Hasan**
