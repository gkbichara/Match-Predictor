# Match Predictor

### Overview

**Match Predictor** is a machine learning project that predicts the outcomes of Premier League matches. Using historical match data, the model is trained to predict the result of future matches based on features such as goals scored, possession, shots on target, and other in-game statistics.

### Features

- Scrapes match data using `BeautifulSoup` from **fbref.com**
- Preprocesses and cleans the data, including handling missing values, encoding categorical features, and normalizing numerical data
- Implements machine learning models (e.g., Random Forest, Logistic Regression) to predict match outcomes
- Evaluates model performance using metrics such as accuracy, precision, and F1-score

### Tech Stack

- **Python**: Core language for data processing and model building
- **BeautifulSoup**: Used for web scraping match data
- **Pandas & NumPy**: Data manipulation and analysis
- **Scikit-Learn**: Machine learning model implementation and evaluation
