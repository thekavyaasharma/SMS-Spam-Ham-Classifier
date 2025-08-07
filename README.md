# SMS Spam Ham Classifier 📱📩

This project implements a machine learning model to classify SMS messages as **spam** or **ham (not spam)** using the **Naive Bayes algorithm**. The dataset consists of labeled SMS messages, and the model uses text preprocessing and vectorization techniques to transform messages into numerical form before classification.

## 📂 Project Structure

- `SMS spam classifier.ipynb`: Main Jupyter notebook containing data analysis, preprocessing, model training (MultinomialNB & BernoulliNB), evaluation metrics, and ROC curve visualization.
- `SMSSpamCollection`: Dataset file containing labeled SMS messages in tab-separated format.
- `requirements.txt`: List of Python libraries used in the project.

---

## 📊 Dataset Description

- **Source**: UCI SMS Spam Collection
- **Format**: Text file with tab-separated values
- **Columns**:
  - `label`: Spam or ham
  - `message`: SMS text

---

## 🧠 Models Used

- **Multinomial Naive Bayes**
- **Bernoulli Naive Bayes**

Both models are trained and evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve

---

## 📈 ROC Curve Comparison

ROC curves are plotted for both MultinomialNB and BernoulliNB models to visually compare their performance. The area under the ROC curve (AUC) is used to evaluate the classification capability.

---

## 📦 Requirements

To run the notebook, install the dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

Main libraries used:
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies
3. Open `SMS spam classifier.ipynb` in Jupyter Notebook
4. Run all cells to train and evaluate the models

---

## 🔍 Results Summary

- ROC curves were generated to compare both models.
- The classification report shows strong performance metrics for both models.
- You can use this pipeline as a baseline for text classification tasks.

---

## ✍️ Author

Kavya Sharma

---

## 📜 License

This project is open source and free to use for educational or non-commercial purposes.
