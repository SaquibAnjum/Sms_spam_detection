# 📩 SMS Spam Detection Using Machine Learning

A Machine Learning based web application that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and a trained ML model.

Built with **Python**, **Scikit-Learn**, and **Streamlit**.

---

## 🚀 Features

* Detects whether an SMS is **Spam** or **Ham**
* Text preprocessing using **NLP**
* User-friendly web interface using **Streamlit**
* Fast and lightweight prediction system
* Trained Machine Learning model with vectorization

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Scikit-Learn**
* **NLTK**
* **Pandas**
* **NumPy**

---

## 📂 Project Structure

```plaintext
SMS_Spam_Detection/
│── app.py
│── model.pkl
│── vectorizer.pkl
│── requirements.txt
│── README.md
│── encoded_spam.csv
│── Naive_Bayes_Project.py
│── Logistic_Regression_Project.py
│── Decision_Tree_Project.py
```

---

## ⚙️ Installation & Setup

### Clone the repository

```bash
git clone [https://github.com/SaquibAnjum/Sms_spam_detection.git]
cd sms-spam-detection
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the Streamlit app

```bash
streamlit run app.py
```

---

## 💡 How It Works

1. User enters an SMS message.
2. Text preprocessing is applied:

   * Lowercasing
   * Tokenization
   * Stopword removal
   * Stemming
3. Text is converted into numerical features using vectorization.
4. The trained machine learning model predicts whether the message is **Spam** or **Ham**.

---

## 📸 Demo

Example Input:

```text
Congratulations! You won a free iPhone. Click here to claim.
```

Output:

```text
Spam
```

---

## 🔮 Future Improvements

* Improve model accuracy
* Add multiple ML model comparison
* Deploy with cloud integration
* Add visualization dashboard

---

## 👨‍💻 Author

**Md Saquib Anjum Khan**

B.Tech CSE Student | IIIT Bhagalpur

GitHub: [https://github.com/SaquibAnjum]
