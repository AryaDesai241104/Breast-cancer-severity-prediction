# 🧠 Breast Cancer Severity Prediction

This project uses machine learning to classify breast cancer tumors as **benign** or **malignant** based on features extracted from cell images. It is built using the **Breast Cancer Wisconsin (Original) Dataset**.

---

## 📂 Project Structure

```

breast-cancer-severity-prediction/
├── data/
│   └── breast-cancer-wisconsin.csv       # Raw dataset
├── notebook/
│   └── breast\_cancer\_severity\_prediction.ipynb  # Jupyter notebook with code and analysis
├── requirements.txt                      # Python dependencies
├── README.md                             # Project overview (you're here!)
└── .gitignore                            # Files ignored by Git

````

---

## 📊 Dataset Overview

- **Source**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original))
- **Instances**: 699
- **Features**:
  - Clump Thickness
  - Uniformity of Cell Size
  - Uniformity of Cell Shape
  - Marginal Adhesion
  - Single Epithelial Cell Size
  - Bare Nuclei
  - Bland Chromatin
  - Normal Nucleoli
  - Mitoses
- **Target Classes**:
  - `2` = Benign
  - `4` = Malignant

---

## ⚙️ Technologies Used

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/breast-cancer-severity-prediction.git
cd breast-cancer-severity-prediction
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the file:

```
notebook/breast_cancer_severity_prediction.ipynb
```

---

## 🔍 Key Features of the Notebook

* ✅ Missing value handling (`'?'` replaced with `NaN`, then filled with median)
* 📊 Exploratory Data Analysis (EDA) with visualizations
* ⚖️ Feature scaling using `StandardScaler`
* 🧠 Model training using `LogisticRegression`
* 📈 Accuracy evaluation and k-fold cross-validation
* 📤 Prediction logic with proper feature formatting

---

## 📈 Results

> **Model Accuracy**: \~`96.42%`
> **Cross-Validation Std. Dev**: \~`1.97%`

## 📚 Acknowledgments

* Dataset: [UCI Breast Cancer Wisconsin (Original)](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28original%29)

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
