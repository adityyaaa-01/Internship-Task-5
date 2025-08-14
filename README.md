# Decision Trees and Random Forest - Internship Task 5

## Overview  
This project implements **Decision Tree** and **Random Forest** models on the **Heart Disease Dataset** to classify patients as having heart disease or not.  
It also covers model visualization, overfitting control, feature importance analysis, and cross-validation.

---

## Steps Followed  

### 1. **Train a Decision Tree Classifier**  
- Fitted a decision tree using all features.  
- Visualized the tree with `plot_tree()`.  

### 2. **Analyze Overfitting and Control Depth**  
- Tested with `max_depth` parameter to reduce complexity.  
- Compared accuracy of full tree vs depth-limited tree.  

### 3. **Train a Random Forest and Compare Accuracy**  
- Used `RandomForestClassifier` with 100 estimators.  
- Compared performance with single decision tree.  

### 4. **Interpret Feature Importances**  
- Extracted and sorted feature importance scores from the random forest.  
- Identified most important predictors (e.g., `cp`, `thal`, `ca`).  

### 5. **Evaluate using Cross-Validation**  
- Performed 5-fold cross-validation on the random forest model.  
- Reported accuracy for each fold and mean CV accuracy.  

---

## Results  

| Model                       | Accuracy |
|-----------------------------|----------|
| Decision Tree (no limit)    | ~98.54%  |
| Decision Tree (max_depth=4) | ~80.00%  |
| Random Forest               | ~98.54%  |
| Mean CV Accuracy (RF)       | ~99.71%  |

---

## How to Run  

1. Clone this repository
2. Install required packages (scikit-learn, matplotlib, etc.)
3. Open the notebook in Jupyter or Colab
4. Run all cells
