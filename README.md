# Amazon Review Intelligence 🛒📊
### Sentiment Analysis Pipeline using VADER & RoBERTa NLP Models

An NLP-powered customer feedback analysis system that analyzes Amazon Fine Food Reviews, compares traditional lexicon-based sentiment analysis with transformer-based models, and uncovers insights beyond star ratings.

The project uses **VADER** and **RoBERTa** to understand customer sentiment, identify rating-sentiment mismatches, and extract actionable insights from large-scale review data.

---

## 🚀 Features

### 📝 Customer Review Analysis
- Processes real-world Amazon customer reviews to understand user opinions and satisfaction patterns.
- Converts unstructured text feedback into meaningful sentiment insights.

### ⚡ Dual Sentiment Analysis Approach
- **VADER Sentiment Analyzer**
  - Fast lexicon-based sentiment scoring
  - Generates positive, neutral, negative, and compound scores

- **RoBERTa Transformer Model**
  - Context-aware sentiment classification
  - Captures deeper meaning and relationships within text

### 📊 Sentiment Comparison
- Compares traditional NLP methods with transformer-based predictions.
- Identifies cases where AI sentiment differs from star ratings.

### 🔍 Customer Experience Insights
- Analyzes:
  - Rating distribution
  - Review length patterns
  - Helpfulness trends
  - Positive and negative feedback patterns

### 💡 Business Intelligence
- Highlights hidden dissatisfaction in highly-rated reviews.
- Helps identify recurring customer pain points and improvement opportunities.

---

# 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| NLP | NLTK, VADER |
| Transformer Model | Hugging Face Transformers, RoBERTa |
| Deep Learning | PyTorch |
| Environment | Jupyter Notebook |

---

# 🧩 How It Works

1. **Dataset Loading**
   - Loaded Amazon Fine Food Reviews dataset containing 568K+ customer reviews.

2. **Data Sampling**
   - Selected a representative sample of 10,000 reviews for efficient transformer-based analysis.

3. **Exploratory Data Analysis**
   - Studied ratings, review lengths, and customer feedback patterns.

4. **Sentiment Prediction**
   - Generated sentiment scores using VADER.
   - Applied RoBERTa transformer model for contextual sentiment classification.

5. **Comparative Analysis**
   - Compared:
     - VADER vs RoBERTa predictions
     - Star ratings vs AI-generated sentiment
     - Sentiment patterns across customer reviews

6. **Business Insights**
   - Converted sentiment results into actionable customer experience recommendations.

---

# 📊 Analysis Performed

### ⭐ Rating Distribution
Understanding customer satisfaction trends through star ratings.

### 🤖 Model Comparison
Evaluating differences between:
- Lexicon-based sentiment analysis
- Transformer-based sentiment analysis

### 🔎 Rating vs Sentiment Analysis
Identifying cases such as:
- Highly rated reviews containing negative feedback
- Low-rated reviews with neutral language

### 📏 Review Length Analysis
Analyzing whether dissatisfied customers provide more detailed feedback.

### 👍 Helpfulness Analysis
Understanding how sentiment influences review usefulness.

---
# 📊 Visualizations

### ⭐ Rating Distribution

![Rating Distribution](visualizations/rating_distribution.png)

Shows the distribution of customer ratings across 1–5 stars.

---

### 🤖 RoBERTa Sentiment Distribution

![RoBERTa Sentiment Distribution](visualizations/roberta_sentiment_distribution.png)

Displays the overall sentiment predicted by the RoBERTa transformer model.

---

### ⚖️ VADER vs RoBERTa Comparison

![Sentiment Comparison](visualizations/sentiment_comparison.png)

Compares sentiment classifications produced by the lexicon-based VADER model and the transformer-based RoBERTa model.

---

### ⭐ Rating vs RoBERTa Sentiment

![Rating vs Sentiment](visualizations/rating_vs_sentiment.png)

Illustrates how customer star ratings align—or differ—from AI-predicted sentiment, highlighting rating-sentiment mismatches.

---

### 📏 Review Length Analysis

![Review Length Analysis](visualizations/review_length_analysis.png)

Compares the average review length across sentiment categories to understand how customer feedback varies.


# 📈 Key Insights

- The dataset shows a strong positive rating bias, with **6,397 out of 10,000 reviews (64%) receiving a 5-star rating**, indicating that most customers expressed positive experiences.

- VADER sentiment analysis classified **8,785 reviews as positive, 1,001 as negative, and 214 as neutral**, highlighting an overall positive customer sentiment trend.

- RoBERTa sentiment analysis identified hidden dissatisfaction within highly-rated reviews. Among **5-star reviews, 145 were classified as negative and 241 as neutral**, showing that numerical ratings alone may not fully capture customer opinions.

- Lower-rated reviews showed stronger negative sentiment patterns. For example, among **1-star reviews, 720 out of 891 reviews were classified as negative by RoBERTa**, demonstrating a strong relationship between rating scores and textual sentiment.

- Review length varied significantly across sentiment categories. Negative reviews had an average length of **446 characters**, compared with **405 characters for positive reviews**, suggesting dissatisfied customers often provide more detailed feedback.
---

# 💼 Business Recommendations

- Combine star ratings with NLP-based sentiment analysis to gain a more complete understanding of customer satisfaction.

- Monitor negative sentiment in highly-rated reviews to identify hidden product issues that traditional rating analysis may overlook.

- Prioritize analysis of longer negative reviews, as they often contain detailed explanations of customer pain points.

- Use automated sentiment classification to categorize large volumes of customer feedback and support faster product improvement decisions.

---

# 📌 Project Highlights

✅ Analyzed 10,000 real customer reviews  
✅ Built an end-to-end NLP sentiment analysis pipeline  
✅ Compared VADER and RoBERTa sentiment approaches  
✅ Performed customer feedback analytics  
✅ Extracted actionable insights from unstructured text data  

---

# 🚀 Future Improvements

- Build an interactive Power BI sentiment dashboard
- Implement topic modeling for automatic complaint categorization
- Create real-time customer feedback monitoring
- Fine-tune RoBERTa on domain-specific review datasets
- Develop automated sentiment reporting pipelines

---


