
# Support Vector Machine (SVM) Classifier

This project demonstrates the implementation of an SVM classifier for a dataset. The process involves data exploration, visualization, and the use of both a basic linear SVM and a tuned SVM model using the RBF kernel with hyperparameter optimization.

## Project Workflow

### 1. **Data Exploration**
- Loaded and inspected the dataset (`cars_dataset.csv`).
- Analyzed feature distributions and relationships.
- Processed categorical features by encoding them into numerical values for compatibility with SVM.

### 2. **Data Visualization**
- Visualized data distributions using histograms and pair plots.
- Explored class distribution and feature relationships.

### 3. **Model Training**

#### Step 1: **Linear SVM**
- Used a basic linear kernel SVM for classification.
- Achieved an accuracy of **70%**.

#### Step 2: **Hyperparameter Tuning**
- Tuned the model to use the **RBF kernel** with **C = 10** for better performance.
- Achieved an accuracy of **100%**.

### 4. **Results Visualization**
- Plotted the decision boundaries for both the linear and tuned models.
- Visualized the performance improvement with hyperparameter tuning.

## Requirements

- Python 3.8+
- Required libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `sklearn`

Install dependencies using:
```bash
pip install -r requirements.txt
```

## Contributions

Feel free to open issues or submit pull requests for improvements!

---

