 E-commerce Customer Review Sentiment Analysis

This project applies text mining and sentiment analysis techniques to Amazon product reviews to understand customer satisfaction drivers and predict product success.

---

 Dataset

- **Source**: [Kaggle - Amazon Product Reviews Dataset](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)
- **File**: `amazon_reviews.csv`
- **Size**: 1,465 rows × 16 columns
- **Content**: Product reviews, star ratings, prices, discounts, and metadata.

---

 Project Objective

**Key Question**  
> How can e-commerce companies use sentiment analysis of product reviews to improve customer satisfaction and predict product performance?

---

 Tools & Methods

- **Language**: Python (Google Colab)
- **Libraries**: pandas, matplotlib, seaborn, nltk, scikit-learn
- **Sentiment Method**: VADER + Logistic Regression
- **Techniques Used**:
  - Data preprocessing & cleaning
  - Sentiment scoring using VADER
  - TF-IDF vectorisation
  - Exploratory data analysis (EDA)
  - Logistic regression classifier
  - Model accuracy testing

---

 Results Summary

- **Model Accuracy**: ~83%
- **Top Positive Keywords**: `durable`, `fast charging`, `good quality`
- **Top Negative Themes**: `stopped working`, `poor build`, `not as described`
- **Findings**: High discount products often show lower satisfaction

---

 Project Structure
ecommerce-sentiment-analysis/
├── amazon_reviews.csv # Dataset
├── sentiment_model.ipynb # Colab notebook (analysis code)
├── milestone_draft.docx # Milestone submission
├── report_draft.docx # Final report (in progress)
└── README.md # Project overview (this file)


---

Author

- [Your Name]
- BAN200 – Summer 2025, Group Project, Seneca College

---

 Contact

If you have questions or ideas, feel free to open an issue or connect via GitHub.

