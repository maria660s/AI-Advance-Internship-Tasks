# 📰 News Topic Classifier using BERT

A transformer-based text classification project that fine-tunes `bert-base-uncased` on the **AG News** dataset to classify news headlines into one of four categories:

- 🌍 **World**
- 🏈 **Sports**
- 💼 **Business**
- 💻 **Sci/Tech**

---

## 🚀 Features

- ✅ Fine-tunes `bert-base-uncased` using Hugging Face Transformers
- 📊 Uses AG News dataset via Hugging Face Datasets
- 🧪 Evaluates performance using **Accuracy** and **F1-score**
- 🌐 Deployed with **Gradio** for real-time headline classification

---

## 📦 Installation

Install required dependencies:

```bash
pip install transformers datasets evaluate scikit-learn gradio
