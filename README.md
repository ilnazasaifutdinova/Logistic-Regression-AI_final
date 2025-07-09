# Logistic-Regression-AI_final

## 🔬 Workflow Pipeline

1. **Data Preprocessing**
   - One-hot encoding, stratified train-test split, scaling

2. **Feature Engineering**
   - Correlation analysis, categorical transformation

3. **Binary Logistic Regression**
   - Manual sigmoid-based model with gradient descent
   - Threshold tuning (0.3, 0.4, 0.5)
   - Evaluation: Accuracy, F1, ROC-AUC

4. **Multinomial Regression**
   - Synthetic dataset generation via `make_classification`
   - Softmax + cross-entropy loss
   - Manual and sklearn comparison

## 📈 Evaluation

| Model                          | Accuracy | F1-score | ROC-AUC |
|-------------------------------|----------|----------|---------|
| Manual Logistic Regression     | 0.56     | 0.30     | 0.49    |
| sklearn LogisticRegression     | 0.56     | 0.30     | 0.49    |
| Softmax (Manual)               | 0.67     | 0.66     | —       |
| Softmax (sklearn Multinomial) | 0.67     | 0.67     | —       |

## 📎 Dataset

- [Kaggle Heart Attack Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset/data)

## 📄 Report

📄 The full IEEE-style report is available in the [`report/`](./report) folder or can be viewed [here (PDF)](https://github.com/ilnazasaifutdinova/Logistic-Regression-AI_final/blob/main/report/Heart_Attack_Logreg_Report.pdf).

## 🚀 Tools Used

- Python 3.12, NumPy, Pandas, scikit-learn
- Jupyter Notebook
- Overleaf (IEEE template)

## 👩‍💻 Author

**Ilnaza Saifutdinova**  
📧 ilnaza.saifutdinova@ue-germany.de  
🌐 [LinkedIn](https://www.linkedin.com/in/ilnaza)

---

