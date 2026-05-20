# Steam Reviews Analytics & Sentiment Classification

## Objective
Applied Data Mining and Natural Language Processing (NLP) techniques on 10,000 Steam reviews to classify player sentiments and uncover hidden feedback trends.

## Technical Toolkit
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **NLP & Feature Extraction:** Text Preprocessing (Cleaning, Stemming), TF-IDF Vectorizer
- **Machine Learning Models:** Logistic Regression, Naive Bayes
- **Clustering:** K-Means Clustering, PCA (Principal Component Analysis)

## Key Results & Methodology
1. **Supervised Learning (Classification):** Compared models for sentiment prediction. **Logistic Regression** outperformed Naive Bayes, achieving a high **84% Accuracy**.
2. **Unsupervised Learning (Clustering):** Implemented K-Means Clustering to group raw text into meaningful themes. Optimized the algorithm by removing domain-specific common words (e.g., 'game', 'play') to surface actual issues.
3. **Insights Extracted:** Successfully segmented player feedback into 3 major operational pillars:
   - **Value & Price:** Discussions regarding cost, DLC value, and worth.
   - **Technical Issues:** Feedback focusing on bugs, crashes, and performance fixes.
   - **Game Experience:** Positive remarks highlighting story, art, and core gameplay.
