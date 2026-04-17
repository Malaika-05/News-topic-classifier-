# News-topic-classifier-
Fine-tuned a BERT-based transformer model for accurate news topic classification using deep learning and NLP techniques

# 📰 News Topic Classifier using BERT

## 📌 Overview

This project is a **Natural Language Processing (NLP) model** that classifies news headlines into different categories using **BERT (Bidirectional Encoder Representations from Transformers)**.

It is built using **Hugging Face Transformers** and demonstrates how modern transformer-based models can be fine-tuned for real-world text classification tasks.

---

## 🚀 Features

* 🧠 Fine-tuned BERT model for text classification
* 📰 Classifies news headlines into multiple categories
* ⚡ High accuracy using transformer architecture
* 📊 Evaluation using standard ML metrics
* 🔁 End-to-end training and inference pipeline

---

## 🧠 Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Scikit-learn
* Pandas, NumPy
* Jupyter Notebook / Google Colab

---

## 📂 Project Structure

```id="bert91x"
├── BERT.ipynb              # Model training and fine-tuning
├── dataset/                # News dataset (if included)
├── model/                  # Saved trained model (optional)
├── tokenizer/              # Tokenizer files (optional)
└── README.md
```

---

## ⚙️ How It Works

1. Load and preprocess news dataset
2. Tokenize text using BERT tokenizer
3. Fine-tune pre-trained BERT model on labeled data
4. Train the model for classification task
5. Evaluate performance using accuracy and F1-score
6. Use trained model for predicting news categories

---

## 📊 Model Details

* Base Model: **BERT (bert-base-uncased)**
* Task: Multi-class text classification
* Input: News headlines
* Output: Predicted news category

---

## 📈 Evaluation Metrics

* Accuracy
* F1 Score
* Loss tracking during training

---

## ▶️ How to Run

1. Clone the repository:

```bash id="run11a"
git clone https://github.com/your-username/news-topic-classifier.git
cd news-topic-classifier
```

2. Install dependencies:

```bash id="run22b"
pip install transformers datasets torch scikit-learn pandas numpy
```

3. Run the notebook:

```bash id="run33c"
jupyter notebook BERT.ipynb
```

---

## 🧪 Example Prediction

Input:

```
"Government announces new education policy for schools"
```

Output:

```
Category: Politics / Education
```

---

## 📚 Learning Outcomes

* Understanding of transformer-based NLP models
* Hands-on experience with BERT fine-tuning
* Data preprocessing for text classification
* Model evaluation and performance tuning
* Real-world NLP application development

---

## 🌱 Future Improvements

* Deploy model using Flask or Streamlit
* Improve dataset size for better accuracy
* Experiment with other transformer models (RoBERTa, DistilBERT)
* Add real-time news API integration

---

## 👩‍💻 Author

**Malaika Taqveem**
BS Artificial Intelligence Student

---

## 📌 Note

This project demonstrates the application of **state-of-the-art NLP techniques** for automated news classification using transformer models.

---

