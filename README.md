# 🌟 Arabic Sentiment Classification of Tweets

This project focuses on classifying Arabic tweets into **positive** or **negative** sentiments using **natural language processing (NLP)** techniques and **machine learning algorithms**. It addresses the unique challenges posed by the Arabic language, such as complex morphology, diverse dialects, and limited datasets.

---

## 🚀 Project Overview

The project utilizes the **Arabic Sentiment Analysis SS2030 Dataset**, which includes:
- **Total Tweets:** 4,252
- **Positive Tweets:** 2,436
- **Negative Tweets:** 1,816

Each tweet is labeled as **0** (Negative) or **1** (Positive). The dataset is split into **80% training** and **20% testing** while maintaining class balance.

---

## 🔧 Key Features

1. **Data Preprocessing:**
   - Extract Arabic words using regular expressions.
   - Remove common stopwords with the NLTK library.
   - Perform stemming using the ISRI Stemmer.

2. **Feature Extraction:**
   - Vectorized text using **TF-IDF**, limited to the top **5,000 features**.

3. **Model Development:**
   - Trained a **Logistic Regression** model with **max_iter=1000** and **random_state=42**.
   - Saved the model and vectorizer using the `pickle` library for future inference.

4. **Evaluation Metrics:**
   - **Accuracy:** Training - 94.2%, Testing - 89.6%.
   - **Precision, Recall, and F1-Score:** Balanced across both classes.

5. **Performance Summary:**
```bash
| Sentiment | Precision | Recall | F1-Score |

| Positive  | 0.91      | 0.88   | 0.89      |

| Negative  | 0.88      | 0.91   | 0.89      |
```
---

## 🖥️ How to Run the Project

1. **Clone the Repository:**
```bash
git clone https://github.com/AbdelkadirSellahi/arabic-sentiment-classification.git
cd arabic-sentiment-classification
```

2. **Install Required Packages:**
```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook:**
```bash
jupyter notebook Arabic_Sentiment_Classification_of_Tweets.ipynb
```

4. **Predict Sentiment:**
Use the saved model to predict sentiment for new Arabic tweets.

---

## 📊 Results and Insights

- The model demonstrated robust performance on real-world Arabic tweets.
- Balanced precision and recall ensured consistent detection of both positive and negative sentiments.
- The **confusion matrix** showed low false positives and false negatives.

---

## 📄 Conclusion

This project successfully developed an efficient sentiment classification system for Arabic tweets using machine learning. It highlights the potential of NLP in analyzing Arabic text while overcoming language complexities. Future improvements could include leveraging deep learning models, expanding datasets, and integrating advanced techniques for higher accuracy and scalability.

---

## 🤝 Contributing

Contributions are welcome! To contribute:
1. **Fork the Repository.**
2. **Create a Feature Branch.**
3. **Commit Changes.**
4. **Push to GitHub and Open a Pull Request.**

---

## 💬 **Contact**

Feel free to open an issue or reach out for collaboration!  

**Author**: *Abdelkadir Sellahi*

**Email**: *abdelkadirsellahi@gmail.com* 

**GitHub**: [Abdelkadir Sellahi](https://github.com/AbdelkadirSellahi)

---

## 🙏 Acknowledgments

- Dataset: **Arabic Sentiment Analysis SS2030 Dataset**.
- Libraries: **NLTK**, **scikit-learn**, **pandas**, **matplotlib**.

---


