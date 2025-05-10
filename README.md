# depression-detection-project
NLP project
# Depression Detection Using NLP

This project uses Natural Language Processing (NLP) techniques to detect signs of depression from text. It compares two deep learning models: a Bidirectional LSTM and a BERT-based Transformer model.

---

## 📁 Project Structure

- `final_project_lstm.py` — Full pipeline for training and predicting with BiLSTM.
- `final_project_transformer.py` — Full pipeline for training and predicting with BERT.
- `checkpoints/` — Model weights and tokenizer (created automatically).
- `requirements.txt` — Required libraries.
- `README.md` — This file.

---

## 💡 Description

The goal is to classify whether a given text indicates a person is depressed or not.

We collected and combined multiple datasets from Kaggle, cleaned the data, and trained two models. Our results showed that BERT outperformed LSTM, especially on longer and more complex texts.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

Install dependencies:

pip install -r requirements.txt

Run the desired model:

# For LSTM
python final_project_lstm.py

# For Transformer (BERT)
python final_project_transformer.py


Note: Each script will automatically load the dataset and save the model into a local checkpoints/ folder.


📚 Datasets

We used publicly available datasets from Kaggle, including:
Depression Reddit Dataset
Suicide Watch Dataset
Sentiment Analysis Tweets
Combined Mental Health Dataset

🛠 Technologies Used
Python 3.x
TensorFlow
Transformers (HuggingFace)
Pandas, NumPy
Google Colab

Authors
yoav jazcilevich



