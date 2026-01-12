#  Project 4: Sentiment Analysis on Text Data

##  Project Overview
This project focuses on building a sentiment analysis system using text data. The objective is to classify text into **negative, neutral, or positive sentiment** using machine learning techniques. The project demonstrates a complete NLP workflow starting from data cleaning to model training and evaluation.

This project helped me understand how text data is processed and converted into numerical form for analysis and how classification models are applied in real-world scenarios.

---

##  Dataset Description
The dataset consists of text samples along with sentiment labels.

### Key Columns:
- `clean_text` – preprocessed text data
- `category` – sentiment label  
  - `-1` → Negative  
  - `0` → Neutral  
  - `1` → Positive  

Rows with missing labels or empty text were removed during preprocessing to maintain data quality.

---

##  Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  
- Matplotlib  
- Seaborn  
- WordCloud  

---

##  Steps Performed

### 1. Data Loading & Exploration
- Loaded the dataset using Pandas
- Checked structure, data types, and missing values

### 2. Data Cleaning
- Removed rows with missing sentiment labels
- Removed empty or blank text entries
- Converted sentiment labels to integer format

### 3. Text Vectorization
- Used **TF-IDF Vectorizer** to transform text into numerical features
- Limited vocabulary size to reduce noise and improve performance

### 4. Train-Test Split
- Split the data into training and testing sets (80/20 split)
- Used a fixed random state for reproducibility

### 5. Model Building
- Implemented **Logistic Regression** for sentiment classification
- Trained the model on TF-IDF features

### 6. Model Evaluation
- Evaluated performance using accuracy score
- Generated classification report and confusion matrix

### 7. Visualization
- Visualized sentiment distribution
- Generated word clouds for different sentiment categories
- Saved all plots in the `visuals` folder

---

##  Results & Insights
- The model successfully classified sentiments into three categories
- TF-IDF helped capture important words influencing sentiment
- Proper data cleaning significantly improved model stability


---

##  Project Structure

Project4_Sentiment_analysis/
│
├── data/
│   └── sentiment_data.csv
│
├── notebooks/
│   └── Sentiment_Analysis.ipynb
│
├── visuals/
│   ├── sentiment_distribution.png
│   ├── wordcloud_positive.png
│   ├── wordcloud_negative.png
│
├── README.md

---

##  Conclusion
This project provided hands-on experience with Natural Language Processing and sentiment classification. It highlights the importance of text preprocessing and feature engineering when working with textual datasets.

---

##  Future Enhancements
- Experiment with different classification models
- Apply hyperparameter tuning for better performance
- Explore deep learning approaches for sentiment analysis

---

##  Author
**Vedaant Lodhi**  
Data Analyst Intern  
Oasis Infobyte

