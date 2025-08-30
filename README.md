A supervised machine learning project that classifies news articles into different categories based on textual patterns and linguistic features. The system employs natural language processing techniques to analyze writing styles, source patterns, and content characteristics from a Kaggle news dataset containing 18,285 articles.

Key Features:
1. Text Preprocessing Pipeline: Implements stemming, stop-word removal, and text normalization
2. Feature Engineering: Uses CountVectorizer with n-grams (1-3) to extract 5,000 linguistic features
3. Multi-Algorithm Approach: Compares MultinomialNB (90.2% accuracy) and PassiveAggressiveClassifier (91.8% accuracy)
4. Comprehensive Evaluation: Includes train/test splits, confusion matrices, and hyperparameter optimization

Technical Implementation:
1. Processes article titles using Porter Stemmer and NLTK
2. Extracts unigrams, bigrams, and trigrams for pattern recognition
3. Identifies distinguishing linguistic markers between article categories
4. Provides interpretable results showing most influential features

Applications: Content categorization, media analysis, journalistic style classification, and automated text sorting systems. This project demonstrates practical NLP techniques for text classification tasks in media and content management domains.
