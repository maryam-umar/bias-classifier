## **Overview**
A machine learning model that classifies news articles as either left or right-leaning, achieving 87.89% accuracy using TF-IDF vectorization and a Passive Aggressive Classifier.

## **Model Performance**

### **Metrics**
- Overall Accuracy: 87.89%
- Left-leaning articles:
 - Precision: 0.91
 - Recall: 0.90
 - F1-score: 0.90
- Right-leaning articles:
 - Precision: 0.83
 - Recall: 0.83
 - F1-score: 0.83

### **Dataset**
- Total samples: 3345 news articles
- Training split: 80%
- Testing split: 20%

## **Model Details**

Algorithm: Passive Aggressive Classifier
- Chosen for its effectiveness in text classification
- Good performance with imbalanced classes
- Fast training and prediction times

Feature Engineering: TF-IDF Vectorization
- Removes common English stop words
- Ignores terms appearing in >70% of articles
- Focuses on distinguishing terms between classes

## **Reflections and Challenges**
Throughout this project, the following have emerged:

**Model Performance**
- The higher accuracy for left-leaning articles (90% F1-score vs 84%) might reflect dataset imbalance
- Model shows moderate confidence in most predictions, suggesting good generalisation

**Technical Challenges**
- Handling class imbalance (more left-leaning articles than right)

**Limitations**
- Binary classification might oversimplify political bias
- Model may be sensitive to specific vocabulary rather than deeper context
- Current scope limited to English language articles

## **References**
1. @mhoali. Right and Left wing news articles with NLP. [cited 2025 Jan 19]. Right and Left wing news articles with NLP. Available from: https://www.kaggle.com/datasets/mhoali/right-and-left-wing-news-articles-with-nlp

2. Pedregosa F, Varoquaux G, Gramfort A, Michel V, Thirion B, Grisel O, et al. Scikit-learn: Machine Learning in Python. MACHINE LEARNING IN PYTHON.
   
3. Riego NCR, Villarba DB. Utilization of Multinomial Naive Bayes Algorithm and Term Frequency Inverse Document Frequency (TF-IDF Vectorizer) in Checking the Credibility of News Tweet in the Philippines [Internet]. arXiv; 2023 [cited 2025 Jan 21]. Available from: http://arxiv.org/abs/2306.00018
   
4. Crammer K, Dekel O, Keshet J, Shalev-Shwartz S, Singer Y. Online Passive-Aggressive Algorithms. 
