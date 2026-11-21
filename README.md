Here is a thorough, well-structured GitHub `README.md` tailored to all 23 of your notebooks. Copy it straight into `README.md` and adjust any folder/file names if you decide to rename typos like `Descion_tree` or `naive-baise.ipynb`.


# Machine Learning Practice Notebooks

A curated archive of **23 Jupyter notebooks** documenting hands-on practice across supervised classification, regression, ensemble tree methods, exploratory data analysis (EDA), data preprocessing, and basic natural language processing (NLP) in Python.

These notebooks were created as learning and experimentation exercises using datasets across healthcare, finance, retail, text, and classic benchmark problems.

---

## Tech Stack & Libraries

- **Language:** Python 3
- **Notebooks:** Jupyter Notebook (`.ipynb`)
- **Data Manipulation & Math:** `numpy`, `pandas`
- **Machine Learning:** `scikit-learn` (`sklearn`)
- **Natural Language Processing:** `nltk`
- **Visualization:** `matplotlib`, `seaborn` *(as used per notebook)*

---

## Repository Structure

```text
MACHINE_LEARNING/
├── Descion_tree/
│   ├── decision_trees/
│   │   ├── breast-cancer-prediction.ipynb
│   │   ├── iris_data_post_prune.ipynb
│   │   └── pre_pruning.ipynb
│   └── Random-Forest/
│       ├── Gold_price.ipynb
│       └── assignment/
│           ├── bigmart.ipynb
│           └── wine_quality.ipynb
├── KNN/
│   └── knn.ipynb
├── Naive_bayes/
│   └── naive-baise.ipynb
├── regression/
│   ├── Boston_housing_price.ipynb
│   ├── Breast_cancer.ipynb
│   ├── credit_card.ipynb
│   ├── diabetes_prdiction.ipynb
│   ├── Evaluating_salary_data.ipynb
│   ├── fakenews.ipynb
│   ├── housing price.ipynb
│   ├── life-expetency.ipynb
│   ├── Logistic_regression.ipynb
│   ├── medical_insurance.ipynb
│   ├── sonar_data.ipynb
│   ├── spam_mail.ipynb
│   └── titatnic_survival.ipynb
├── SVM/
│   └── Parkinson_disease.ipynb
└── titanic_EDA_prediction.ipynb

```

---

## Notebooks Overview

### 1. Decision Trees & Random Forests (`Descion_tree/`)

#### Decision Trees (`decision_trees/`)

* **`breast-cancer-prediction.ipynb`** — Binary classification workflow on breast cancer data, covering data loading, model training, and evaluation metrics.
* **`iris_data_post_prune.ipynb`** — Explores post-pruning techniques on a decision tree trained on the Iris dataset to manage overfitting.
* **`pre_pruning.ipynb`** — Explores pre-pruning / tree complexity constraints on the Iris dataset.

#### Random Forests (`Random-Forest/`)

* **`Gold_price.ipynb`** — Examines feature correlations and modeling relationships on gold price data.
* **`assignment/bigmart.ipynb`** — Data preprocessing and modeling assignment on BigMart retail sales data.
* **`assignment/wine_quality.ipynb`** — Modeling and evaluation assignment on wine quality data.

---

### 2. Classification Models (`KNN/`, `Naive_bayes/`, `SVM/`)

* **`KNN/knn.ipynb`** — K-Nearest Neighbors classification workflow (including train/test splitting on the Iris dataset).
* **`Naive_bayes/naive-baise.ipynb`** — Probabilistic classification using `GaussianNB` with feature scaling (`StandardScaler`) and classification evaluation metrics.
* **`SVM/Parkinson_disease.ipynb`** — Support Vector Machine (`svm`) classification workflow for Parkinson's disease prediction, including data inspection, preprocessing, and accuracy evaluation.

---

### 3. Regression, Tabular & NLP Workflows (`regression/` & Root)

#### Regression & Numerical Prediction

* **`Boston_housing_price.ipynb`** — Housing price prediction and regularization experiments (such as Ridge regression for overfitting).
* **`housing price.ipynb`** — Additional housing price regression practice notebook.
* **`Evaluating_salary_data.ipynb`** — Salary prediction and regression evaluation.
* **`life-expetency.ipynb`** — Modeling life expectancy across dataset features.
* **`medical_insurance.ipynb`** — Medical insurance cost modeling with categorical feature handling.

#### Classification, Imbalanced Data & Signal Data

* **`Logistic_regression.ipynb`** — Binary/multi-class classification using logistic regression.
* **`Breast_cancer.ipynb`** — Breast cancer classification workflow within the regression/tabular practice folder.
* **`diabetes_prdiction.ipynb`** — Diabetes prediction workflow on tabular health data.
* **`credit_card.ipynb`** — Credit card fraud detection focusing on handling heavily imbalanced datasets.
* **`sonar_data.ipynb`** — Classification on sonar signal data.

#### Natural Language Processing (NLP)

* **`fakenews.ipynb`** — Text classification workflow for fake news detection using text preprocessing/vectorization (`nltk` / `TfidfVectorizer`).
* **`spam_mail.ipynb`** — Spam email classification workflow with missing-value/text preprocessing steps.

#### Exploratory Data Analysis (EDA)

* **`titanic_EDA_prediction.ipynb`** *(Root)* & **`regression/titatnic_survival.ipynb`** — Exploratory data analysis, outlier/missing-value handling, and survival prediction on the Titanic dataset.

---

## Getting Started

1. **Clone the repository:**
```bash
git clone <your-repo-url>
cd MACHINE_LEARNING

```


2. **Create and activate a Python environment:**
```bash
conda create -n ml-practice python=3.11 -y
conda activate ml-practice

```


3. **Install common dependencies:**
```bash
pip install jupyter notebook numpy pandas scikit-learn nltk matplotlib seaborn

```


4. **Launch Jupyter Notebook:**
```bash
jupyter notebook

```



---

## Important Notes on Reproducibility

* **Dataset Paths:** Several notebooks were originally written on a local Windows setup. If a cell fails on `pd.read_csv(...)`, update the file path to point to your local copy of the dataset.
* **Practice & Experimental Nature:** Because these notebooks were built during hands-on learning, some include exploratory cells, print statements, or overlapping experiments (such as multiple Titanic or Breast Cancer notebooks).
* **Large Files & Artifacts:** Raw datasets, trained model binaries, and Jupyter checkpoint folders should be excluded via `.gitignore` when pushing to GitHub.

```

