
---

# **AI-Powered Course Recommender System for TVET Learners**

---

## **Project Overview**

This project is an **AI-based course recommender system** that predicts suitable trades for TVET learners using personality traits and demographic features. It uses **XGBoost** and **LightGBM** for multi-class predictions, providing robust course recommendations.

---

## **Key Features**

* Predicts trades based on personality and demographic info
* Handles missing data, outliers, and categorical encoding
* Scales numeric features for model optimization
* Implements **XGBoost** & **LightGBM** classifiers
* Hyperparameter tuning via `RandomizedSearchCV`
* Evaluation metrics: Accuracy, F1, Precision, Recall, ROC-AUC, MRR, NDCG, MCC, Cohen’s Kappa

---

## **Methodology**

1. **Data Preprocessing** – Clean, encode, and scale features
2. **Train-Test Split** – 80% train, 20% test
3. **Model Training** – XGBoost & LightGBM classifiers
4. **Hyperparameter Tuning** – RandomizedSearchCV
5. **Evaluation** – Classification & ranking metrics

---

## **Model Performance (Placeholder)**

| Model    | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
| -------- | -------- | --------- | ------ | -------- | ------- |
| XGBoost  | 0.XXXX   | 0.XXXX    | 0.XXXX | 0.XXXX   | 0.XXXX  |
| LightGBM | 0.XXXX   | 0.XXXX    | 0.XXXX | 0.XXXX   | 0.XXXX  |

---

## **Usage**

1. Clone the repository:

```bash
git clone https://github.com/yourusername/tvet-course-recommender.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Load your dataset and run the notebook to preprocess, train, and evaluate models.
4. Use the trained model to generate course recommendations for new learners.

---

## **Dependencies**

* Python 3.x
* `pandas`, `numpy`, `scikit-learn`, `xgboost`, `lightgbm`, `matplotlib`, `seaborn`, `scipy`, `google-colab`

---

## **Contributing**

Contributions are welcome! Submit issues or pull requests to improve the system or add features.

---

## **License**

MIT License – Open-source project

---

