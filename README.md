## 💬Natural Language Processing

A structured collection of **NLP concepts, implementations, experiments, and practical notebooks** documenting my journey from raw text preprocessing to word embeddings and an end-to-end text classification pipeline.

This repository focuses on understanding **how machines process and learn from human language**, combining conceptual understanding with practical implementations using Python, NLTK, Gensim, and scikit-learn.

---

## 📚 What This Repository Covers

The repository follows a progressive learning path, starting from cleaning raw text and gradually moving toward word embeddings and a deployable text classifier.

### 1. 🧹 Text Preprocessing

Preparing raw text so that it can be used by machine learning models.

Topics include:

- Text Cleaning
- Lowercasing
- Tokenization
- Stopword Removal
- Stemming
- Lemmatization

---

### 2. 🏷️ Part-of-Speech (POS) Tagging

Assigning grammatical categories to words in a sentence.

Topics include:

- Part-of-Speech Tagging
- Tag Sets
- Sequence Labeling
- Practical POS Tagging with Python

---

### 3. 🔢 Word Embeddings (Word2Vec)

Representing words as dense vectors that capture meaning and similarity.

Topics include:

- Word Embeddings
- Word2Vec
- Word Similarity
- Training Word2Vec on a Custom Corpus
- Game of Thrones Word2Vec Experiment

---

### 4. 📩 SMS Spam Detection (End-to-End Pipeline)

Building a complete text classification workflow from raw messages to a saved model.

Topics include:

- Text Preprocessing Pipeline
- Feature Extraction
- Model Training
- Model Evaluation
- Saving a Trained Pipeline with Joblib
- Predicting on New Messages

---

## 🛠️ Technologies & Tools

The notebooks and implementations in this repository primarily use:

- 🐍 **Python**
- 🔢 **NumPy**
- 📊 **Pandas**
- 📚 **NLTK**
- 🧠 **Gensim**
- 🤖 **scikit-learn**
- 💾 **Joblib**
- 📓 **Jupyter Notebook**

---

## 🎯 Learning Approach

Each topic is studied through a combination of:

**Concept → Implementation → Experiment → Observation**

The goal is not only to use NLP libraries, but to understand the ideas behind text processing and language representation.

---

## 📂 Repository Structure

```
NLP/
│
├── text-preprocessing.ipynb
├── pos-tagging.ipynb
├── word2vec_demo.ipynb
├── game-of-thrones-word2vec.ipynb
├── end_to_end_nlp_pipeline_sms_spam_detection_assigment_2.py
├── sms_spam_pipeline.joblib
├── NLP.pdf
└── README.md
```

> *The structure may evolve as new concepts and experiments are added.*

---

## 💡 Key Concepts

| Area | Concepts |
| --- | --- |
| Text Preparation | Tokenization, Stopwords, Stemming, Lemmatization |
| Linguistic Analysis | POS Tagging |
| Word Representation | Word2Vec, Word Embeddings, Word Similarity |
| Text Classification | Spam Detection, Pipelines, Model Saving |
| Libraries | NLTK, Gensim, scikit-learn |

---

## 🚀 Purpose

The main objectives of this repository are to:

- Build a strong foundation in Natural Language Processing
- Understand how raw text is prepared for machine learning
- Learn how words are represented as vectors
- Implement an end-to-end NLP pipeline
- Gain practical experience with NLTK, Gensim, and scikit-learn
- Build a strong foundation for advanced topics such as **RNNs, Transformers, and LLMs**

---

## 📈 Learning Progress

```
Python & Text Basics
        ↓
Text Preprocessing
        ↓
POS Tagging
        ↓
Word Embeddings (Word2Vec)
        ↓
End-to-End Text Classification Pipeline
        ↓
🚀 Deep Learning for NLP & Transformers
```

---

## 📌 Highlights

✨ Hands-on text preprocessing workflow  
✨ POS tagging experiments  
✨ Word2Vec trained on a real text corpus  
✨ End-to-end SMS spam detection pipeline  
✨ Saved model ready for reuse  
✨ Jupyter-based practical experimentation

---

## ⚙️ Getting Started

```bash
git clone https://github.com/rajanprasad3/NLP.git
cd NLP
pip install nltk gensim scikit-learn pandas numpy joblib jupyter
jupyter notebook
```

Using the saved spam model:

```python
import joblib

model = joblib.load("sms_spam_pipeline.joblib")
print(model.predict(["You won a free prize! Call now."]))
```

---

## 👨‍💻 Author

**Rajan Prasad**

BS Computer Science & Data Analytics  
Indian Institute of Technology Patna

### 🔗 Connect

- GitHub: [Rajan Prasad](https://github.com/rajanprasad3)
- Resources: CampusX NLP YouTube Playlist

---

## ⭐ Repository

If you find this repository useful for learning NLP, feel free to **⭐ star the repository** and explore the notebooks.

---

### 📖 References

- [CampusX: Natural Language Processing (NLP) course page](https://learnwith.campusx.in/courses/Natural-Language-Processing---NLP-YouTube-691466e7be8ce103a29dbff8)
- [NLTK Documentation](https://www.nltk.org/)
- [Gensim Word2Vec Documentation](https://radimrehurek.com/gensim/models/word2vec.html)
- Mikolov et al. (2013), [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/dataset/228/sms+spam+collection)
- Jurafsky & Martin, [Speech and Language Processing (3rd ed. draft)](https://web.stanford.edu/~jurafsky/slp3/)
