##  Technologies Used

- Python 3.11
- Pandas
- NumPy
- Scikit-learn (sklearn)
- Jupyter Notebook

---

##  ML Workflow

1. **Data Cleaning**
   - Replaced null values with empty strings.
   - Converted labels to binary (spam = 1, ham = 0).

2. **Text Vectorization**
   - Used `TfidfVectorizer` to convert messages into numerical feature vectors.

3. **Model Training**
   - Split data into training and test sets.
   - Trained a `LogisticRegression` model.

4. **Evaluation**
   - Used `accuracy_score` to evaluate performance on both training and test data.

---

## Model Accuracy

- Training Accuracy: ~99%
- Test Accuracy: ~97–98%  
(Note: Accuracy may vary slightly depending on the random seed in train/test split.)

---

