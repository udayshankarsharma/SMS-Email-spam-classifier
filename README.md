# 📧 SMS/Email Spam Classifier 🚀

An end-to-end Machine Learning project that classifies SMS and Email messages as **Spam** or **Not Spam** using **Natural Language Processing (NLP)** and **Multinomial Naive Bayes**, deployed with a **Streamlit web application**.

---

## 🔥 Features

* 📩 Detects Spam and Not Spam messages
* 🧠 NLP-based text preprocessing
* 📊 TF-IDF vectorization
* ⚡ Fast and efficient Naive Bayes model
* 🌐 Interactive UI built with Streamlit
* 🎯 High accuracy (~95–97%)

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy
* **NLP:** NLTK
* **Frontend:** Streamlit

---

## 🧠 Machine Learning Pipeline

```
Text Input
   ↓
Lowercase Conversion
   ↓
Tokenization
   ↓
Remove Stopwords & Punctuation
   ↓
Stemming
   ↓
TF-IDF Vectorization
   ↓
Multinomial Naive Bayes
   ↓
Prediction (Spam / Not Spam)
```

---

## 📂 Project Structure

```
sms-email-spam-classifier/
│
├── app.py                      # Streamlit app
├── model.pkl                  # Trained model
├── vectorizer.pkl             # TF-IDF vectorizer
├── spam.csv                   # Dataset
├── requirements.txt           # Dependencies
├── sms-spam-detection.ipynb   # Model training notebook
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/sms-email-spam-classifier.git
cd sms-email-spam-classifier
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate (Windows):

```bash
venv\Scripts\activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Application

```bash
streamlit run app.py
```

---

## 🌐 Usage

1. Enter a message in the input box
2. Click on **Predict**
3. View result:

   * ❌ Spam
   * ✅ Not Spam

---

## ⚠️ Important Notes

### 🔹 NLTK Setup

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

### 🔹 Version Compatibility

Ensure correct version of scikit-learn:

```txt
scikit-learn==1.5.0
```

---

## 📊 Model Performance

* **Model:** Multinomial Naive Bayes
* **Accuracy:** ~95–97%
* **Precision:** High for spam detection

---

## 💡 Future Improvements

* Add confidence score (% probability)
* Improve UI design
* Deploy using Docker
* Build REST API (FastAPI)
* Multi-language support

---

## 👨‍💻 Author

**Uday Sharma**
B.Tech CSE Student | ML & Data Science Enthusiast

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 📢 Share it

---

## 📜 License

This project is licensed under the MIT License.
