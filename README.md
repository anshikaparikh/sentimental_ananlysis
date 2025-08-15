# sentimental_ananlysis
## 📌 Project Overview
This project performs **Sentiment Analysis** on a small dataset of movie reviews.  
It classifies each review as **Positive** or **Negative** using Natural Language Processing (NLP) and Machine Learning techniques.

---

## 🛠 Technologies Used
- **Python**
- **Pandas** for data handling
- **NLTK** for text preprocessing (stopwords removal)
- **Scikit-learn** for vectorization and model building
- **Logistic Regression** for classification

---

## 📂 Dataset
The dataset contains **16 sample movie reviews** (balanced positive and negative).  
Each review is labeled with its sentiment.

Example:
| Review | Sentiment |
|--------|-----------|
| "Amazing direction and great storyline!" | Positive |
| "Worst movie ever. Complete waste of time." | Negative |

---

## ⚙ Steps Performed

1. **Data Preparation**  
   - Created a sample dataset of movie reviews.
   - Added sentiment labels: `positive` / `negative`.

2. **Text Preprocessing**  
   - Converted text to lowercase.
   - Removed punctuation.
   - Removed stopwords using **NLTK**.

3. **Feature Extraction**  
   - Used **TF-IDF Vectorization** to convert text into numerical form.

4. **Model Building**  
   - Trained a **Logistic Regression** model to classify sentiments.

5. **Evaluation**  
   - Calculated Accuracy and Classification Report.
   - Tested the model with sample inputs.
