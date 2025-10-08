## Premium Health Insurance Charges Prediction

This project focuses on **predicting health insurance premium charges** based on multiple individual and lifestyle factors such as **age, sex, BMI, number of children, smoking habits, and region**. It leverages **machine learning models** to provide accurate and data-driven estimates of insurance charges.

---

## 🧠 Project Overview

The goal of this project is to develop a predictive model that estimates health insurance costs based on demographic and health-related features. It demonstrates the complete workflow of:

* Data preprocessing and exploratory data analysis (EDA)
* Model training and evaluation using supervised learning algorithms
* Visualization of decision trees and insights into feature importance

---

## 📂 Project Structure

```
Premium-Health-Insurance-Charges-Prediction/
│
├── LICENSE                          # Licensing information
├── README.md                        # Project overview and documentation
├── requirements.txt                 # Python package dependencies
│
├── Data/                            # Dataset files used for model training
│   └── insurance.csv
│
├── Notebook/                        # Jupyter Notebooks for EDA, model training & evaluation
│   └── Premium_Insurance_Prediction.ipynb
│
├── src/                             # Source code for scripts & utility functions
│   └── decision_tree_visualization.py
│
└── Decision Tree results/            # Visualizations and PDFs of decision tree models
    ├── tree_raw.dot
    └── tree_visualization.pdf
```

---

## ⚙️ Requirements

The following Python libraries are required:

* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`

You can install all dependencies at once using the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

---

## 🚀 Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/Premium-Health-Insurance-Charges-Prediction.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd Premium-Health-Insurance-Charges-Prediction
   ```

3. **Install required dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## 🧩 Usage

To explore, train, and evaluate the model:

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Notebook/Premium_Insurance_Prediction.ipynb
   ```
2. Run all cells to:

   * Load and preprocess the dataset
   * Visualize correlations and feature distributions
   * Train ML models (e.g., Linear Regression, Decision Tree)
   * Evaluate model performance metrics (MAE, RMSE, R²)
   * Visualize the decision tree structure

---

## 📊 Outputs

* **Trained model results**
* **Decision tree visualizations** (in `.dot` and `.pdf` formats)
* **Statistical and graphical analysis** of features and predictions
Use the scripts in the src/ directory for tasks like decision tree visualization.
The output visualizations can be found in the Decision Tree results/ directory.

