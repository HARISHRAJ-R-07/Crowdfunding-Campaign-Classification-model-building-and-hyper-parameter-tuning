# 🎯 Crowdfunding Campaign Success Prediction

> A machine learning classification project to predict whether a crowdfunding campaign will be successful using campaign-related data.

## 📌 Project Overview

Crowdfunding allows individuals and organizations to raise funds from a large number of supporters. The goal of this project is to analyze crowdfunding campaign data and build machine learning classification models to predict campaign success.

This project covers data exploration, preprocessing, categorical encoding, feature selection, model building, evaluation, cross-validation, and hyperparameter tuning.

## 🎯 Project Objectives

* Explore and preprocess the crowdfunding dataset.
* Handle categorical variables using encoding techniques.
* Identify relevant features for classification.
* Train and compare multiple machine learning models.
* Evaluate model performance using accuracy, precision, recall, and F1-score.
* Apply cross-validation and hyperparameter tuning.
* Identify the best-performing model based on evaluation results.

## 📂 Project Structure

```text
Crowdfunding-Classification/
│
├── Crowdfunding_Classification.ipynb
├── Crowdfunding_Classification_Report.pdf
├── README.md
├── requirements.txt
│
└── plots/
    ├── correlation_heatmap.png
    ├── model_comparison.png
    └── model_metrics_comparison.png
```

## 📊 Dataset

**Dataset:** Crowdfunding Campaign Dataset

[View and download the dataset](https://raw.githubusercontent.com/GeethaGunasekaran1/Dataset_rep/refs/heads/main/crowdfunding.csv)

The dataset contains campaign-related information, including category, launch month, country, currency, goal amount, raised amount, campaign duration, number of backers, owner experience, and video inclusion.

**Target variable:** `IsSuccessful`

The target indicates whether a crowdfunding campaign was successful.

## 🛠️ Technologies and Libraries

* **Python** — programming language
* **Pandas** — data manipulation and analysis
* **NumPy** — numerical computing
* **Matplotlib** — data visualization
* **Seaborn** — statistical visualization
* **Scikit-learn** — machine learning, preprocessing, and evaluation
* **Google Colab / Jupyter Notebook** — development environment

## 🔄 Project Workflow

1. **Data Exploration:** Inspect the dataset, data types, missing values, duplicates, and unique categorical values.
2. **Data Preprocessing:** Remove unwanted columns and prepare the data for analysis.
3. **Categorical Encoding:** Apply label encoding and one-hot encoding where appropriate.
4. **Feature Selection:** Examine feature correlations and use SelectKBest with an ANOVA F-test.
5. **Train-Test Split:** Separate the data into training and testing sets.
6. **Feature Scaling:** Apply feature scaling as implemented in the notebook.
7. **Model Building:** Train five classification algorithms.
8. **Model Evaluation:** Compare accuracy, precision, recall, F1-score, and confusion matrices.
9. **Cross-Validation:** Evaluate model stability using stratified cross-validation.
10. **Hyperparameter Tuning:** Search for suitable model parameters using GridSearchCV and RandomizedSearchCV.
11. **Model Comparison:** Compare the tuned models and identify the best-performing classifier.

## 🤖 Machine Learning Algorithms

The following classification algorithms were evaluated:

* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier
* Gaussian Naive Bayes
* Support Vector Classifier (SVM)

## 📈 Model Evaluation Results

The following results are from the saved model comparison in the notebook.

| Model                           | Accuracy | Precision | Recall | F1-Score |
| ------------------------------- | -------: | --------: | -----: | -------: |
| Support Vector Classifier (SVM) |   99.77% |    99.92% | 99.63% |   99.77% |
| Decision Tree Classifier        |   99.34% |    99.43% | 99.26% |   99.34% |
| Random Forest Classifier        |   97.92% |    98.77% | 97.06% |   97.90% |
| K-Nearest Neighbors (KNN)       |   78.43% |    79.99% | 76.02% |   77.95% |
| Gaussian Naive Bayes            |   66.20% |    72.82% | 52.06% |   60.71% |

### 🏆 Best-Performing Model

The **Support Vector Classifier (SVM)** achieved the highest reported accuracy of approximately **99.77%** in the notebook's final model comparison.

These results should be validated carefully before making real-world claims. Check for data leakage, target-derived features, and correct fitting of preprocessing and feature-selection steps within the training data and cross-validation process.

## 📉 Visualizations

### Correlation Heatmap

![Correlation Heatmap](plots/correlation_heatmap.png)

### Model Accuracy Comparison

![Model Accuracy Comparison](plots/model_comparison.png)

### Precision, Recall, and F1-Score Comparison

![Model Metrics Comparison](plots/model_metrics_comparison.png)

## ▶️ How to Run This Project

### Option 1: Google Colab

1. Open Google Colab.
2. Upload `Crowdfunding_Classification.ipynb`.
3. Run the notebook cells in the correct order.
4. Make sure the dataset URL is accessible.
5. Review the charts, evaluation metrics, and model comparison results.

### Option 2: Run Locally

Clone or download this repository, then install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `Crowdfunding_Classification.ipynb` and execute the cells.

## 💡 Key Takeaways

* Explored and prepared crowdfunding campaign data for machine learning.
* Practiced categorical encoding and feature selection.
* Built and evaluated five classification algorithms.
* Applied cross-validation and hyperparameter tuning.
* Compared models using multiple evaluation metrics.
* Identified SVM as the highest-scoring model in the saved comparison.

## 🚀 Future Improvements

* Verify that there is no data leakage.
* Use a reproducible preprocessing and modeling pipeline.
* Validate results with stratified cross-validation and unseen test data.
* Investigate the most influential campaign features.
* Test the final model on new campaign records.
* Improve the reporting and deployment of the selected model.

## 👨‍💻 Author

**Harish Raj R.**

Aspiring Data Science Professional | Python | Machine Learning | Data Analysis

🔗 **GitHub:** [HARISHRAJ-R-07](https://github.com/HARISHRAJ-R-07)

---

⭐ If you find this project interesting, consider starring the repository!
