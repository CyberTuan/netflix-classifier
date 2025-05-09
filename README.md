# netflix-classifier

A beginner machine learning project using the Netflix dataset to predict whether a title is a Movie or a TV Show

##  🧠  Model
This project uses a **Random Forest Classifier** from 'Scikit-learn' trained on:
_ Country of production
_ Release year
_ Duration (e.g., 90 min or 2 seasons)

**** Achieved ~98% accuracy on test data.

##  📁  Files
_ 'netflix_classifier.ipynb' - the complete training notebook
_ 'netflix_titles.csv' - the dataset
_ 'netflix_model.pk1' the saved machine learning model


## 🛠️  Tools Used 
_ Python + Pandas
_ Scikit-learn (Label Encoder, Train/Test Split, RandomForestClassifier)
_ Google Colab
_ SQLite


## 📊 Results
| Metric     | Score |
|------------|--------|
| Accuracy   | 98.05% |
| Precision  | 0.97–0.98 |
| Recall     | 0.96–0.99 |
| F1-Score   | 0.97–0.99 |


##  🚀  How to Run
1. Clone the repo or download the notebook
2. Upload 'netflix.titles.csv' to Colab
3. Run all cell in 'netflix_classifier.ipynb'
4. Modify and retrain the model if desired!

---

## Future Improvements 
_ Build a Streamlit web app interface
_ Use more advanced NLP on the Description field
_ Host the model with FLask or FastAPI

**⭐ Star the repo if you found this helpful!**
