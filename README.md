# 🧠 Children Mental Health Analysis

This project explores data-driven insights into children's mental health by combining text mining of research papers with machine learning analysis of survey datasets. It aims to identify key behavioral, social, and emotional factors associated with mental well-being.

## 📂 Project Structure
| Folder / File | Description |
|----------------|-------------|
| `data/raw/` | Original datasets (train/test/data dictionary) |
| `data/processed/` | Processed outputs such as filtered essays & NLP results |
| `notebooks/Article Scraping.ipynb` | Web scraping academic papers |
| `notebooks/text_mining_part.ipynb` | Text mining and keyword analysis |
| `notebooks/EDA&Preprocessing&ML.ipynb` | EDA, feature engineering, and ML modeling |
| `README.md` | Project documentation |

## 🧩 Workflow Overview

### 1. Article Scraping
- **Goal:** Collect and filter open-access academic articles related to children’s mental health.  
- **Process:**  
  - Scrape abstracts and metadata from research databases.  
  - Filter based on keywords and text length.  
  - Export the cleaned dataset to `data/processed/filtered_essays_info_50_pages.csv`.

### 2. Text Mining
- **Goal:** Perform NLP analysis to uncover common mental health themes.  
- **Process:**  
  - Tokenization, TF-IDF vectorization, and word frequency analysis.  
  - Visualize keyword patterns to highlight major focus areas in research.

### 3. EDA, Preprocessing & Machine Learning
- **Goal:** Analyze structured mental health survey data.  
- **Process:**  
  - Conduct exploratory data analysis (EDA) and feature preprocessing.  
  - Implement PCA for dimensionality reduction.  
  - Build and evaluate ML models (e.g., XGBoost, Random Forest) to identify key predictors.

## 🧠 Key Insights
- Extracted **research focus clusters** from 200+ academic papers.  
- Identified **behavioral and demographic indicators** strongly linked to mental health risk.  
- Built models with interpretable features to support policy and educational interventions.


