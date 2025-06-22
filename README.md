# 🛒 Flipkart Reviews Sentiment Analysis

This project focuses on performing sentiment analysis on product reviews from Flipkart. The goal is to classify reviews as positive or negative using Natural Language Processing (NLP) techniques and machine learning models. The dataset was sourced from GeeksforGeeks (GFG) and includes user-generated product reviews.

---

## 📌 Project Workflow

The project is structured into the following key steps:

1. **Importing Libraries and Dataset**  
   - Loaded necessary Python libraries for data handling, visualization, and NLP.
   - Imported the review dataset from GFG.

2. **Preprocessing the Data**  
   - Cleaned text by removing punctuation, stopwords, and converting to lowercase.
   - Tokenization and lemmatization using **NLTK**.

3. **Visualizing the Data**  
   - Used **Seaborn** and **Matplotlib** to understand the distribution of review sentiments.

4. **Generating WordClouds**  
   - Created word clouds for positive reviews to visualize common words and sentiments.

5. **Vectorizing the Text**  
   - Converted text data into numerical format using **TF-IDF** from **Scikit-learn**.

6. **Model Training**  
   - Trained machine learning models (e.g., Logistic Regression) to classify reviews.

7. **Model Evaluation and Prediction**  
   - Evaluated model performance using metrics like **accuracy**, **precision**, and **confusion matrix**.

---

## 🧰 Libraries Used

- **Pandas** – Data manipulation and analysis  
- **Scikit-learn** – ML modeling and vectorization  
- **NLTK** – Natural language processing  
- **Matplotlib** – Data visualization  
- **Seaborn** – Enhanced visualizations  
- **WordCloud** – Generate word cloud from review text

---

## 🧪 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/flipkart-sentiment-analysis.git
   cd flipkart-sentiment-analysis
