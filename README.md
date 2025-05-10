# depression-detection-project
NLP project
# Depression Detection Using NLP

This project uses Natural Language Processing (NLP) techniques to detect signs of depression from text. It compares two deep learning models: a Bidirectional LSTM and a BERT-based Transformer model.

## 📁 Project Structure
- `final_project_lstm.ipynb` — Full pipeline for training and predicting with BiLSTM.  
- `final_project_transformer.ipynb` — Full pipeline for training and predicting with BERT.  
- `checkpoints/` — Model weights and tokenizer (created automatically).  
- `requirements.txt` — Required libraries.  
- `README.md` — This file.

## 💡 Description
The goal is to classify whether a given text indicates a person is depressed or not.

We collected and combined multiple datasets from Kaggle, cleaned the data, and trained two models. Our results showed that BERT outperformed LSTM, especially on longer and more complex texts.

## 🚀 How to Run

You can run the code using Google Colab:

- Open the desired notebook (`.ipynb`) in Colab  
- Make sure the `checkpoints/` folder is created (it happens automatically)  
- Run all cells from top to bottom  

> Note: All scripts automatically download the data, process it, and save the model into a local `checkpoints/` folder.

## 📚 Datasets Used
We used publicly available datasets from Kaggle, including:

- Depression Reddit Dataset  
- Suicide Watch Dataset  
- Sentiment Analysis Tweets  
- Combined Mental Health Dataset  

## 🛠 Technologies
- Python 3.x  
- TensorFlow  
- HuggingFace Transformers  
- Pandas, NumPy  
- Google Colab

## 👤 Author
Yoav Jazcilevich




