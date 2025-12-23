# 📰 Fake News Detection using BERT

## 📌 Project Overview

This project focuses on detecting **fake news articles** using **Natural Language Processing (NLP)** and **Deep Learning** techniques. The core of the system is built using **BERT (Bidirectional Encoder Representations from Transformers)**, a state-of-the-art transformer-based language model that understands contextual meaning in text.

The model classifies news articles as **Fake** or **Real** by learning semantic patterns from labeled datasets. This project demonstrates practical application of NLP, transfer learning, and text classification.

---

## 🚀 Key Features

* Uses **pre-trained BERT model** for contextual text understanding
* Binary classification: **Fake vs Real News**
* End-to-end NLP pipeline (data cleaning → tokenization → modeling → evaluation)
* High accuracy due to transformer-based architecture
* Implemented fully in **Python (Jupyter Notebook)**

---

## 🧠 Technologies Used

* Python
* Jupyter Notebook
* TensorFlow / PyTorch (BERT backend)
* Hugging Face Transformers
* Scikit-learn
* Pandas, NumPy
* Matplotlib / Seaborn

---

## 📊 Dataset Description

The project uses two publicly available CSV datasets:

* **True News Dataset (`True.csv`)** – Contains legitimate and verified news articles.
* **Fake News Dataset (`Fake.csv`)** – Contains fabricated or misleading news articles.

Both datasets include textual news content along with labels. They are merged and labeled as:

* `1` → Real News
* `0` → Fake News

The combined dataset is shuffled and split into **training and testing sets** for model evaluation.

---

## 📂 Project Structure

```
├── b1_BERT_Walkthrough.ipynb      # Step-by-step explanation of BERT
├── b2_FakeNewDetection.ipynb     # Fake news detection using BERT
├── x1_FakeNewDetection.ipynb     # Extended / experimental version
├── dataset/                      # News dataset (CSV)
├── requirements.txt              # Required Python libraries
└── README.md                     # Project documentation
```

---

## 🔄 Workflow

1. **Data Collection** – Load labeled fake & real news dataset
2. **Data Preprocessing**

   * Text cleaning
   * Lowercasing
   * Removing stopwords
3. **Tokenization** using BERT tokenizer
4. **Model Building**

   * Pre-trained BERT model
   * Classification head
5. **Training & Fine-Tuning**
6. **Model Evaluation**

   * Accuracy
   * Precision
   * Recall
   * F1-score
7. **Prediction on New News Articles**

---

## 📊 Model Performance

* Achieves **high accuracy** due to contextual embeddings
* Performs well on unseen news articles
* Reduces false positives compared to traditional ML models

*(Exact metrics may vary based on dataset split and training parameters)*

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/fake-news-detection-bert.git
cd fake-news-detection-bert
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open and execute the notebooks in sequence.

---

## 🧪 Sample Output

* Input: *"Government confirms alien invasion"*

* Prediction: **Fake News ❌**

* Input: *"RBI announces new monetary policy"*

* Prediction: **Real News ✅**

---

## 📌 Use Cases

* Social media misinformation detection
* News verification platforms
* Journalism fact-checking tools
* Academic research in NLP

---

## 👨‍💻 Author

**Ayush Yadav**
AI & Machine Learning Enthusiast

---
