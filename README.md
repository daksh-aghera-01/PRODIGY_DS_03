# Bank Marketing - Decision Tree Classifier

This project uses the [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) to build a **Decision Tree Classifier** that predicts whether a customer will subscribe to a term deposit.

## 📁 Project Structure
```
├── data/               → Contains the dataset (`bank-full.csv`)
├── notebook/           → Jupyter notebook with full analysis
├── src/                → (Optional) Python script for reusable model code
├── requirements.txt    → Python dependencies
├── .gitignore          → Files and folders to be ignored by Git
└── README.md           → Project overview
```

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook notebook/Task\ 3.ipynb
   ```

## 🧠 Model
- Model: `DecisionTreeClassifier` from `sklearn`
- Target: `y` — whether the customer subscribed (`yes`/`no`)
- Encoding: All categorical features label-encoded

## 📊 Evaluation
Includes:
- Accuracy
- Classification report
- Confusion matrix
- Tree visualization

## 📎 Dataset Source
[Bank Marketing Data Set - UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
