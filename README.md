# 💳 Credit Card Fraud Detection

A **Machine Learning project** to detect fraudulent credit card transactions using **anomaly detection techniques**.
The project leverages **Isolation Forest, Local Outlier Factor (LOF), and One-Class SVM** to identify unusual patterns in highly imbalanced datasets.

---

## 📊 Problem Statement

Credit card fraud is a growing problem with millions of people affected each year.
This project aims to detect fraudulent transactions by:

* Using **unsupervised anomaly detection methods**
* Handling highly **imbalanced datasets**
* Evaluating performance with **precision, recall, and accuracy**

---

## 🚀 Features

* 📂 Load and preprocess the **Credit Card Fraud Detection dataset**
* 📉 Handle **imbalanced class distribution** (normal vs fraud)
* 🧠 Implement **3 anomaly detection models**:

  * Isolation Forest
  * Local Outlier Factor (LOF)
  * One-Class SVM
* 📊 Evaluate performance using metrics:

  * Accuracy
  * Precision
  * Recall
  * F1-score

---

## 🛠️ Tech Stack

* **Programming Language**: Python 🐍
* **Libraries**:

  * NumPy, Pandas – Data handling
  * Matplotlib, Seaborn – Visualization
  * Scikit-learn – ML models & evaluation
  * SciPy – Numerical operations

---

## 📂 Project Structure

```bash
Credit-Card-Fraud-Detection/
│── kk_project_3.ipynb     # Jupyter Notebook (main project)
│── creditcard.csv         # Dataset (Kaggle Credit Card Transactions)
│── requirements.txt       # Dependencies
│── README.md              # Documentation
```

---

## ⚡ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook kk_project_3.ipynb
```

---

## 📊 Dataset

* Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
* Transactions: **284,807**
* Fraud cases: **492 (0.172%)** → highly **imbalanced**

Each transaction includes anonymized features (V1–V28), transaction time, amount, and class label (0 = normal, 1 = fraud).

---

## 🧠 Models Implemented

### 1. Isolation Forest 🌲

* Detects anomalies by randomly selecting features and splitting values.
* Efficient for high-dimensional datasets.

### 2. Local Outlier Factor (LOF) 📍

* Measures local density deviation of data points.
* Flags points that are in regions of lower density.

### 3. One-Class SVM 🌀

* Finds a decision boundary around the majority class.
* Flags outliers that fall outside this boundary.

---

## 📈 Evaluation

Sample metrics (from notebook results):

| Model              | Accuracy | Precision | Recall | F1-score |
| ------------------ | -------- | --------- | ------ | -------- |
| Isolation Forest   | 99.74%   | 31%       | 28%    | 29%      |
| Local Outlier Fact | 99.65%   | 14%       | 34%    | 20%      |
| One-Class SVM      | 99.52%   | 13%       | 50%    | 21%      |

*(Note: Metrics may vary depending on random seed & hyperparameters.)*

---

## 🔮 Future Enhancements

* ⚖️ Use **SMOTE / oversampling techniques** for balancing dataset
* 🧾 Try **deep learning models (Autoencoders, LSTMs)**
* 📊 Build a **dashboard (Streamlit / Flask)** for real-time fraud detection
* 🏗 Deploy as an **API / Web service**

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. Fork the repository
2. Create a new branch (`git checkout -b feature-xyz`)
3. Commit changes (`git commit -m "Added new feature"`)
4. Push to branch (`git push origin feature-xyz`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Krishna Kumar Ranjan**
📧 \[krishnaranjan1111@gmail.com]

---

✨ If you found this project helpful, don’t forget to **star ⭐ the repo**!
