# 🤖 Predictive Modeling Using Machine Learning

## 🎯 Objective
This project is part of the **Thiranex Data Science Internship** (Task 2). The objective is to gain practical experience in supervised learning, model evaluation, and predictive analytics by building a robust machine learning classification model.

## 📊 Dataset Description
We utilize the **Breast Cancer Wisconsin (Diagnostic) Dataset**. Features are computed from digitized images of a fine needle aspirate (FNA) of breast mass, describing the characteristics of the cell nuclei present. The target variable is binary, indicating whether a tumor is malignant or benign, making it an ideal candidate for classification algorithms.

## 🛠️ Key Features & Methodology
1. **Data Preprocessing:** Handled features and separated the target variable for training.
2. **Train-Test Split:** Split the dataset into 80% training data and 20% testing data to ensure objective evaluation.
3. **Model Selection:** Implemented a **Random Forest Classifier** (`n_estimators=100`) due to its robustness against overfitting and its high performance in tabular classification tasks.
4. **Model Evaluation:**
   - Generated a detailed **Classification Report** (Precision, Recall, F1-Score).
   - Plotted a **Confusion Matrix** heatmap to visualize True Positives, True Negatives, False Positives, and False Negatives.
   - Plotted a **Receiver Operating Characteristic (ROC) Curve** and calculated the Area Under Curve (AUC) to evaluate the model's diagnostic ability.

## 📈 Expected Outcome Achieved
Gained hands-on experience in supervised learning model deployment, binary classification metrics, and evaluating algorithms using confusion matrices and ROC curves.

## 💻 Technologies Used
- **Python 3.10**
- **Scikit-Learn** (Machine Learning, Train/Test Split, Metrics)
- **Pandas** (Data structures)
- **Matplotlib & Seaborn** (Visualizing Confusion Matrix & ROC curves)

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/predictive_modeling.ipynb
   ```
4. Run all cells sequentially to observe the model training process and final accuracy visualizations.
