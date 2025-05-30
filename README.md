# 🔍 k-Nearest Neighbors Classification on Large Kitchen Appliances Dataset

This notebook applies the k-Nearest Neighbors (k-NN) algorithm to classify appliance energy data.  
It was originally submitted as a course assignment and showcases a full ML workflow using `.arff`-formatted data.

---

## 📌 Project Overview

- **Goal**: Predict categorical class labels for appliances based on numeric features
- **Dataset**: LargeKitchenAppliances_TRAIN.arff & LargeKitchenAppliances_TEST.arff
- **Techniques**:
  - k-NN modeling using `sklearn`
  - Grid search with cross-validation
  - Accuracy evaluation and model tuning

---

## 🧠 Key Concepts

- Handling `.arff` data with `scipy.io.arff`
- Preprocessing and label formatting
- Hyperparameter tuning with `GridSearchCV`
- Model evaluation using `cross_val_score` and `StratifiedKFold`

---

## 📁 Files

| File                                | Description                        |
|-------------------------------------|------------------------------------|
| `k-Nearest Neighbors Homework.ipynb` | Main notebook                      |
| `LargeKitchenAppliances_TRAIN.arff` | Training dataset                   |
| `LargeKitchenAppliances_TEST.arff`  | Testing dataset                    |
| `README.md`                         | Project summary (this file)        |

---

## 🚀 How to Run

1. Place both `.arff` files in the same directory as the notebook
2. Open the notebook in Jupyter
3. Run all cells to reproduce the training, tuning, and evaluation process

---

## 📈 Output

- Final accuracy scores
- Best value for `k`
- Validation framework using `StratifiedKFold`

---

## 🧰 Tools Used

- Python 3.x
- `scikit-learn`
- `pandas`, `numpy`, `seaborn`, `matplotlib`
- `scipy.io.arff`

---

This notebook is suitable for use in a machine learning portfolio to demonstrate classification model tuning and `.arff` data handling.
