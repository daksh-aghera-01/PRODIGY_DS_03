# 🎯 Decision Tree Classifier – Bank Marketing Dataset

This project demonstrates how to use a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit, using demographic and behavioral data collected by a Portuguese bank during a direct marketing campaign.

## 📊 Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **File used**: `bank-full.csv`
- **Records**: 45,211
- **Target Variable**: `y` (yes = subscribed, no = not subscribed)

## 🧪 Objective
To train and evaluate a **Decision Tree Classifier** that uses customer information (age, job, marital status, balance, etc.) to predict if a customer will subscribe to a term deposit.

## 📁 Folder Structure
```
decision-tree-bank-marketing/
├── data/
│   └── bank-full.csv
├── notebooks/
│   └── decision_tree_classifier.ipynb
├── outputs/
│   ├── decision_tree_plot.png
│   └── confusion_matrix.png
├── requirements.txt
└── README.md
```

## 🔧 Project Steps
1. Load Dataset
2. Explore and Clean
3. Preprocessing (Label Encoding)
4. Split Dataset
5. Train Model
6. Evaluate Model
7. Visualize Tree

## 📦 Requirements
```bash
pip install -r requirements.txt
```

## 🚀 Run the Notebook
```bash
jupyter notebook notebooks/decision_tree_classifier.ipynb
```

## 💡 Future Enhancements
- Try RandomForestClassifier
- Add GridSearchCV
- Use SHAP or LIME for explainability

## 🧑‍💻 Author
- **Your Name** – [@yourgithub](https://github.com/yourgithub)

## 🪪 License
MIT License
