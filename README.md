# Time-Travelling-News-Analyzer-Project
Time-Traveling News Analyzer is a Python and pandas-based data science project that explores how media coverage of topics like AI or climate change has evolved over time. It analyzes historical news data to uncover trends in sentiment, language, and media bias, using NLP, visualizations, and optional interactive dashboards.

# 🕒 Time-Traveling News Analyzer  
**Author**: Karan  

## Project Overview  
The **Time-Traveling News Analyzer** is a data science and NLP project that explores how news media sentiment and keyword usage have evolved over time. Using historical headlines, the tool provides visual and machine learning–driven insights into how media tone and focus shift year by year.

---

## Key Objectives

- Analyze the sentiment of news headlines from different years.
- Track frequency trends of keywords like "AI", "climate", "machine".
- Visualize sentiment and keyword evolution with plots and word clouds.
- Train a machine learning model to classify the sentiment of headlines.

---

## Main Components

### 1. Data Handling  
The project loads a dataset containing historical news headlines and their publication dates.

### 2. Text Preprocessing  
Each headline is cleaned by removing punctuation, converting to lowercase, and simplifying the text structure for analysis.

### 3. Sentiment Analysis  
The polarity of each headline is calculated using the **TextBlob** library. Headlines are labeled as:
- Positive
- Neutral
- Negative

### 4. Trend Visualization  
-  **Sentiment Trend Over Time**: Average sentiment per year
-  **Word Cloud**: Shows most common words used in headlines
-  **Keyword Frequency**: Yearly trend of keywords like `ai`, `climate`, `machine`, `change`

### 5. Machine Learning Model  
A logistic regression model is trained to predict sentiment (positive, neutral, or negative) using TF-IDF vectorized features.

### 6. Evaluation  
The model is evaluated using:
- Classification Report (precision, recall, f1-score)
- Confusion Matrix

---

##  Tools & Technologies

| Tool            | Purpose                          |
|-----------------|----------------------------------|
| `pandas`        | Data handling                    |
| `numpy`         | Numerical operations             |
| `matplotlib`    | Plotting                         |
| `seaborn`       | Advanced visualization           |
| `textblob`      | Sentiment analysis               |
| `wordcloud`     | Word frequency visualization     |
| `scikit-learn`  | Machine learning model training  |
| `nltk`          | Natural language preprocessing   |

---

##  Use Cases

- Media bias and sentiment tracking
- Political and environmental news analysis
- Educational NLP/ML portfolio project

---

##  Future Enhancements

- Analyze larger datasets from news APIs or archives
- Add interactive dashboard (e.g., using Streamlit)
- Improve sentiment classification with advanced NLP models like **BERT**
- Add topic modeling to identify evolving themes


