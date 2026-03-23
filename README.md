# 📘 Word2Vec from Scratch + Financial NLP Dataset

## 🚀 Overview

This project implements **Word2Vec (Skip-Gram with Negative Sampling)** from scratch and applies it to a **financial news dataset (Infosys news)**. It demonstrates how word embeddings capture semantic relationships in real-world financial text.

The project is designed for:

* 🎓 PhD / Research in NLP & Finance
* 📊 Quantitative Finance & Algorithmic Trading
* 🤖 Deep Learning & Representation Learning

---

## 🧠 Key Concepts Covered

* One-Hot Encoding
* Distributional Hypothesis
* Word Embeddings
* CBOW & Skip-Gram Models
* Negative Sampling
* Hierarchical Softmax
* Cosine Similarity
* Vector Arithmetic (Analogies)

---

## ⚙️ Implementation Details

* 🔹 Built **Word2Vec from scratch using NumPy**
* 🔹 Skip-Gram architecture
* 🔹 Negative Sampling optimization
* 🔹 Custom preprocessing pipeline:

  * Text cleaning
  * Stopword removal
  * Rare word filtering
* 🔹 Trained on **financial news corpus (Infosys)**

---

## 📊 Dataset

* Source: Google News (Infosys-related headlines)
* Size: ~100 news samples
* Processed into:

  * Cleaned corpus
  * Tokenized word list
  * Training pairs

---

## 🔍 Sample Results

### Similar Words (Learned Embeddings)

```
infosys → shares, growth, forecast, revenue  
market → stocks, trading, benchmarks  
growth → revenue, demand, expansion  
```

👉 Demonstrates that the model captures **financial semantics** from limited data.

---

## 📈 Model Pipeline

```
Raw News Data
    ↓
Text Cleaning & Preprocessing
    ↓
Vocabulary Building
    ↓
Training Pair Generation
    ↓
Word2Vec Training (Skip-Gram)
    ↓
Embedding Space
    ↓
Similarity & Analysis
```

---

## 🧪 How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/word2vec-financial-nlp.git
cd word2vec-financial-nlp
```

2. Install dependencies:

```
pip install numpy pandas
```

3. Run the notebook or script:

```
python word2vec.py
```

---

## 🎯 Applications

* 📊 Financial Sentiment Analysis
* 📈 Stock Direction Prediction
* 📰 News Embedding for Trading Signals
* 🔍 Semantic Search in Financial Data

---

## ⚠️ Limitations

* Small dataset (titles only)
* No contextual embeddings (static vectors)
* Limited semantic depth compared to BERT

---

## 🔬 Future Work

* ✅ Train on full financial news corpus (2015–2026)
* ✅ Integrate with FinBERT embeddings
* ✅ Add bigrams (e.g., `stock_market`, `revenue_growth`)
* ✅ Visualize embeddings using t-SNE
* ✅ Integrate into LSTM/GRU stock prediction models

---

## 📚 References

* Mikolov et al. (2013) – Efficient Estimation of Word Representations
* Stanford CS224N (NLP with Deep Learning)
* MIT Deep Learning Lectures
* IIT Bombay NLP Course

---

## 👨‍💻 Author

**Kamal Gavel**
PhD Researcher – AI/ML in FinTech
📍 India

---

## ⭐ If you found this useful

Give a ⭐ on GitHub and feel free to contribute!
