# Sentiment Analysis with NLP: End-to-End Pipeline

### *¿What is NLP?*
Natural Language Processing (NLP) is a field at the intersection of linguistics, computer science, and artificial intelligence. It focuses on enabling machines to understand, interpret, and generate human language. NLP powers a wide range of applications such as chatbots, sentiment analysis, machine translation, and more.

---
🧠 This repository presents a complete Natural Language Processing (NLP) pipeline focused on sentiment analysis, covering all the core stages of a classic NLP project. Each stage is implemented in an independent Jupyter notebook, with reusable and modular code. This project is ideal for understanding the full workflow of text classification in a real-world scenario.

### 📂 Project Structure

```bash
nlp_sentiment_analysis/
│
├── 1_data_exploration.ipynb           # Exploratory Data Analysis (EDA) of the corpus
├── 2_text_preprocessing.ipynb         # Text cleaning and preprocessing functions
├── 3_model_training.ipynb             # Model training and evaluation (BoW + ML models)
├── 4_final_report.ipynb               # Metrics, analysis, and conclusions
├── requirements.txt                   # Required libraries
└── README.md                          # Project documentation
```


### 🚀 Project Objectives
1. Download and Explore the Corpus
   - Vocabulary size and distribution
   - Distribution of reviews by rating
   - Count of positive vs negative reviews
   - Most frequent n-grams
   - Word clouds
   - Word embeddings visualization with Word2Vec
   - Conclusions and insights from data exploration

2. Text Preprocessing
   - Development of a modular preprocessing function in Python
   - Typical steps: lowercasing, punctuation removal, stopwords removal, stemming/lemmatization, etc.
   - Designed for reusability and clarity

3. Model Training and Evaluation
    -Binary sentiment classification (positive vs negative)
   - Bag-of-Words (BoW) representation
   - Training of two different models (e.g., Logistic Regression, Random Forest, SVM, etc.)
   - Evaluation based on metrics: precision, recall, F1-score
   - Analysis of class balance and vectorizer configuration

4. Final Report
   - Metric comparison and final model selection
   - Strengths, weaknesses, and limitations of the approach
   - Suggestions for future improvements


### 🛠 Technologies Used
- Python
- pandas, numpy – Data manipulation and analysis
- matplotlib, seaborn, wordcloud – Data visualization
- nltk, spacy – Text preprocessing and NLP utilities
- gensim – Word2Vec embeddings
- scikit-learn – Machine learning models and evaluation
- Jupyter Notebook – Interactive experimentation

### 📌 Future Improvements
* Integrate TF-IDF or pretrained embeddings
* Experiment with deep learning models (e.g., LSTM, BERT)
* Deploy as an API for real-time sentiment classification

### 🧠 Author
Proyecto académico desarrollado con fines educativos para consolidar conocimientos en procesamiento de lenguaje natural y machine learning aplicado.


