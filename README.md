# Classifying Investor Sentiment Using Machine Learning

## Project Overview
This project, developed as part of a summer course in Data Science at the University of Notre Dame, applies machine learning techniques to classify investor sentiment using market indicators and economic data. The study uses data from multiple sources including the AAII Sentiment Survey, S&P 500, USDX futures, and US Treasury Bond futures to predict bullish-bearish spread in investor sentiment.

## Key Findings
The analysis demonstrated that market indicators can effectively classify investor sentiment, with K-Nearest Neighbors achieving 74% accuracy and K-Means clustering correctly separating 67% of bullish-bearish sentiments, significantly outperforming random chance in a binary classification task.

*For the complete analysis and methodology, please refer to the full project paper: `classifying_investor_sentiment_paper.pdf`*

## Technical Stack
- **Python** - Primary programming language
- **Pandas** - Data manipulation and preprocessing
- **Scikit-learn** - Machine learning implementation
- **Jupyter Notebooks** - Interactive development
- **Quandl** - Financial data API integration
- **Matplotlib** - Data visualization

## Repository Structure
- `data preparation_shivpalit.ipynb` - Data collection and preprocessing notebook
- `data analysis_shivpalit.ipynb` - Machine learning analysis notebook
- `data/` - Directory containing project datasets

## Data Sources
- AAII Investor Sentiment Survey
- S&P 500 data (Yahoo Finance)
- USDX futures data (Quandl)
- US Treasury Bond futures data (Quandl)
- Dow Jones Industrial Average (Yahoo Finance)
- NASDAQ Composite (Yahoo Finance)

## Running the Analysis
1. Install required Python packages:
```
pandas
scikit-learn
quandl
matplotlib
numpy
```
2. Execute the data preparation notebook to process raw data
3. Run the analysis notebook to perform machine learning classification
