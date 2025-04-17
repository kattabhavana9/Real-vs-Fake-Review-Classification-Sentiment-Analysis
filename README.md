# Real vs Fake Review Classification & Sentiment Analysis

A machine learning-based system to detect fake reviews, analyze sentiment, and visualize patterns in review data.

## 📌 Features
- **Fake Review Detection**: Classifies reviews as real or fake using ML models.
- **Sentiment Analysis**: Determines sentiment (Positive/Negative/Neutral) of genuine reviews.
- **Data Visualization**: Generates word clouds, confusion matrices, and sentiment distributions.

## 📊 Dataset
- **Sources**: Amazon/Yelp reviews, synthetic datasets.
- **Features**:
  - Review text
  - Rating (1-5 stars)
  - Label (Real/Fake)
  - Metadata (User profile, timestamps)

## 🛠️ Technologies Used
### Machine Learning Models
- Random Forest
- Logistic Regression
- XGBoost
- SVM
- Naive Bayes

### NLP Processing
- Text cleaning (lowercase, punctuation removal)
- Tokenization & Stopword removal
- Stemming/Lemmatization
- CountVectorizer/TF-IDF

### Visualization
- Word Clouds
- Confusion Matrices
- Sentiment Distribution Plots

## ⚙️ Workflow
1. **Data Collection**: Scraped or pre-loaded datasets.
2. **Preprocessing**: Text cleaning & feature engineering.
3. **Model Training**: Multiple ML classifiers.
4. **Evaluation**: Accuracy, Precision, Recall, F1-Score.
5. **Deployment**: (Optional) Flask/Streamlit web app.

## 📈 Results
| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| **Random Forest**   | 92%      | 0.91      | 0.93   | 0.92     |
| **XGBoost**         | 90%      | 0.89      | 0.91   | 0.90     |
| **Logistic Regression** | 88%  | 0.87      | 0.89   | 0.88     |

**Best Model**: Random Forest (92% accuracy)

## 🔍 Key Insights
- **Fake Reviews** often:
  - Use exaggerated language ("Best ever!!!")
  - Lack detail/generic phrasing
  - Have inconsistent timestamps
- **Real Reviews** show:
  - Balanced sentiment distribution
  - Specific product experiences

## 🚀 Future Improvements
- **Deep Learning**: BERT/Transformers for contextual analysis.
- **Live Detection**: Browser extension for real-time fake review flagging.
- **Multilingual Support**: Non-English review processing.
