# *Sentiment Analysis with NLP: End-to-End Pipeline*

### *¿What is NLP?*
*Natural Language Processing (NLP) is a field at the intersection of linguistics, computer science, and artificial intelligence. It focuses on enabling machines to understand, interpret, and generate human language. NLP powers a wide range of applications such as chatbots, sentiment analysis, machine translation, and more.*

---
*This repository presents a complete Natural Language Processing (NLP) pipeline focused on sentiment analysis, covering all the core stages of a classic NLP and including Machine Learning techniques to classify gourmet product reviews into two categories: positive reviews (1) and negative reviews (0).*


## 📌 *Project Objectives* 
1. ***Download and Explore the Corpus***:
   - *Vocabulary size and distribution*
   - *Distribution of reviews by rating*
   - *Count of positive vs negative reviews*
   - *Most frequent n-grams*
   - *Word clouds*
   - *Word embeddings visualization with Word2Vec*
   - *Conclusions and insights from data exploration*

2. ***Text Preprocessing***:
   - *Development of a modular preprocessing function in Python.*
   - *Typical steps: lowercasing, punctuation removal, stopwords removal, stemming/lemmatization, etc.*
   - *Designed for reusability and clarity*

3. ***Model Training and Evaluation***:
    -*Binary sentiment classification (positive vs negative)*
   - *2 different types of vectorization (`CountVectorizer`,  `TF-IDF`).*
   - *Training of 4 different models (KNN, Logistic Regression, Random Forest, SVM).*
   - *Evaluation based on metrics: precision, recall, F1-score.*
   - *Analysis of class balance and vectorizer configuration*

4. ***Final Report***:
   - *Metric comparison and final model selection*
   - *Strengths, weaknesses, and limitations of the approach*
   - *Suggestions for future improvements*


##  ⚙️ *Technologies Used*

  | *Área*              | *Herramientas y librerías* |
|-------------------|--------------------------|
| *Manipulación de datos* | `pandas`, `numpy`|
| *Visualización* | `matplotlib`, `seaborn`, `plotly` |
| *Text preprocessing* | `nltk`,` spacy` |
| *imblearn* | *Balanceo de clases* (`RandomOverSampler`)
| *scikit-learn* | *Machine learning models and evaluation*|


---

### *Future Improvements*

* *Incorporate pre-trained embeddings (word2vec, GloVe, BERT) to capture the semantic context.*
* *Explore Deep Learning architectures (CNNs, RNNs, Transformers)*.
* *Deploy as an API for real-time sentiment classification.*

## ⚠️ *Disclaimer*
*This project was developed as part of an academic exercise to reinforce practical skills in Natural Language Processing (NLP) and applied Machine Learning. The dataset used is publicly available and attributed to [Julian McAuley (University of California, San Diego)](https://jmcauley.ucsd.edu/data/amazon/).*

*Course instructors provided some portions of the code, and they have been reused where appropriate. Additionally, AI-assisted tools were used to complement the development process in line with academic integrity and learning objectives*.


