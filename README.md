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

# 📈 Key Insights

*(To be updated with final analysis results)*

- Customer ratings alone may not fully represent customer sentiment.
- Transformer-based models identify contextual dissatisfaction hidden in reviews.
- Negative reviews often provide detailed explanations of customer issues.
- Combining rating data with NLP sentiment provides a more complete view of customer experience.

---

# 💼 Business Impact

This project demonstrates how NLP can help businesses:

- Monitor customer satisfaction at scale
- Automatically categorize feedback
- Identify recurring product issues
- Improve customer experience strategies
- Make data-driven product decisions

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

# 📂 Repository Structure
