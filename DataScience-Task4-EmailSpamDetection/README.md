# Task 4: Email Spam Detection with Machine Learning

## Project Overview
This project uses Natural Language Processing (NLP) and Machine Learning to classify text messages as **Spam** or **Ham (Legitimate)**.

The project uses the SMS Spam Collection dataset and demonstrates how machine learning algorithms can identify unwanted messages.

## Dataset
- **Dataset:** SMS Spam Collection Dataset
- **Source:** [Kaggle – SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Original records:** 5,572 messages
- **Records after cleaning:** 5,169 messages

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- NLTK
- WordCloud

## Project Workflow
1. Loaded and explored the dataset.
2. Removed unnecessary columns and duplicate records.
3. Analyzed the distribution of spam and ham messages.
4. Preprocessed text by converting it to lowercase, removing punctuation and numbers, and removing stopwords.
5. Converted text into numerical features using TF-IDF.
6. Split the dataset into training and testing sets.
7. Trained two machine learning models:
   - Multinomial Naive Bayes
   - Logistic Regression
8. Evaluated both models using accuracy, precision, recall, F1-score, and confusion matrices.
9. Generated WordCloud visualizations for spam and ham messages.
10. Tested the trained model using sample messages.

## Model Performance

| Metric | Multinomial Naive Bayes | Logistic Regression |
|---|---:|---:|
| Accuracy | 96.71% | 94.68% |
| Precision | 98.99% | 97.50% |
| Recall | 74.81% | 59.54% |
| F1-Score | 85.22% | 73.93% |

## Conclusion
Multinomial Naive Bayes performed better than Logistic Regression across all four evaluation metrics, achieving an accuracy of 96.71%.

The project demonstrates how NLP and machine learning techniques can be used to classify messages as spam or ham.

## How to Run
1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud
   ```
4. Open `email_spam_detection.ipynb` in Jupyter Notebook.
5. Run the notebook cells from top to bottom.

**Note:** This project uses an SMS dataset to demonstrate spam detection through text classification. It is a learning project and is not intended as a production-ready email filtering system.