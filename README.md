# Heart_Disease_Project
This project predicts the likelihood of heart disease in patients using clinical and demographic data.  
It covers data preprocessing, dimensionality reduction, supervised and unsupervised learning, hyperparameter tuning.

###  Preprocessing
- Handled missing values  
- Applied StandardScaler  
- One-hot encoding for categorical features  
- PCA for dimensionality reduction

- Heart_Disease_Project/
- 
│── data/                 # Dataset

│── notebooks/            # Jupyter notebooks (01–06)

│── models/               # Trained models (.pkl)

│── results/              # Evaluation results (txt, plots)

│── README.md

│── requirements.txt

│── .gitignore

## Model Performance

### Supervised Learning
| Model                | Accuracy | Precision | Recall | F1-score | AUC   |
|-----------------------|----------|-----------|--------|----------|-------|
| Logistic Regression   | 0.8833   | 0.8889    | 0.8571 | 0.8727   | 0.9397 |
| Decision Tree         | 0.6667   | 0.6818    | 0.5357 | 0.6000   | 0.6685 |
| Random Forest         | 0.8333   | 0.8750    | 0.7500 | 0.8077   | 0.9319 |
| SVM                   | 0.8333   | 0.8462    | 0.7857 | 0.8148   | 0.9431 |
