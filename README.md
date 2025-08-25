# 📰 Fake News Detection with Deep Learning

## 📌 Overview
This project demonstrates how **Deep Learning** can be applied to detect fake news articles.  
Using natural language processing (NLP) and deep learning models, we classify news as either **Fake** or **Real** based on their text content.
This project involved identifying when an article might be fake news. In this, I used a dataset named "Fake and real news” from Kaggle

The project is implemented in **Python** using **Jupyter Notebook**.
## 📂 Project Structure
- `fake-news-detection.ipynb` → Main notebook containing the full workflow  
- `data/` → Dataset directory (to be added by user)  
- `requirements.txt` → Python dependencies (create using `pip freeze > requirements.txt`)  

---

## ⚙️ Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Swathi97054/Fake-News-detection-with-DL.git
   cd Fake-News-detection-with-DL
2. Create a virtual environment:

```bash 
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```
## Libraries
pandas, 
numpy,
keras,
tensorflow,
scikit-learn, and 
LSTM Neural Network

# 📊 Dataset

The project uses the Fake News Dataset (commonly available on Kaggle):

Dataset contains news articles with labels:

1 → Fake

0 → Real

You can download the dataset from Kaggle and place it in the data/ folder.

 ## 🧠 Models Used

The notebook experiments with:

Text Preprocessing (stopword removal, tokenization, TF-IDF/word embeddings)

Deep Learning Models:

1. LSTM (Long Short-Term Memory)

2. Bidirectional LSTM

3. GRU (Gated Recurrent Unit)

4. CNN for text classification

## 🚀 Usage

Run the notebook step by step:

Data loading & cleaning

Text preprocessing

Model training

Evaluation (accuracy, precision, recall, F1-score)

## 📈 Results

Achieved high accuracy in detecting fake news

Demonstrates the power of deep learning over traditional ML approaches

After training for 5 epochs, the model achieved an accuracy of 99.27% in detecting fake news.
