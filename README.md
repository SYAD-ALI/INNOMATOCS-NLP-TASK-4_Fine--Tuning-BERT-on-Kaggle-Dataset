# NLP Internship Task 4 – Fine-Tuning BERT on IMDB Dataset

## 👤 Student Details
**Name:** Syad Ali  
**Internship ID:** IN126055102  

---

## 📌 Overview
This project focuses on building a text classification model by fine-tuning a pre-trained BERT model on the IMDB movie reviews dataset. The goal is to classify reviews as positive or negative using Natural Language Processing techniques.

---

## 🎯 Objectives
- Understand how BERT works for text classification
- Perform fine-tuning using Hugging Face Transformers
- Apply tokenization using pre-trained models
- Evaluate model performance using multiple metrics

---

## 🛠️ Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Google Colab

---

## 📂 Dataset
- IMDB Movie Reviews Dataset
- Contains 50,000 labeled reviews (positive/negative)

---

## 🔄 Project Pipeline
Raw Data → Preprocessing → Tokenization → Model Training → Evaluation → Comparison

---

## ⚙️ Steps Involved

### 1. Data Preprocessing
- Converted text to lowercase
- Removed HTML tags and special characters
- Handled missing values

### 2. Tokenization
- Used `bert-base-uncased` tokenizer
- Converted text into tokens suitable for BERT

### 3. Model Building
- Used `AutoModelForSequenceClassification`
- Loaded pre-trained BERT model

### 4. Fine-Tuning
- Optimizer: AdamW
- Learning Rate: 2e-5
- Trained model on dataset

### 5. Model Evaluation
Evaluated model using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🧪 Experiments
- Trained full BERT model
- Compared performance with different settings
- Analyzed results for better understanding

---

## 📊 Results
The model achieved good performance in classifying sentiments with high accuracy and balanced precision-recall values.

---

## 🚀 How to Run
1. Open the notebook in Google Colab  
2. Install required libraries:
   ```bash
   !pip install transformers datasets scikit-learn
