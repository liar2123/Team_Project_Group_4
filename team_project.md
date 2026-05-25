# AASD 4001: Mathematical Concepts for Machine Learning
## School of Computer Technology — Term Project Specification

> [!NOTE]
> **Active Developer Profile**: **Kris**
> **Assignments**: **Random Forest** (Approach C)

---

### 📋 Overview
This project requires obtaining a large classification dataset and applying several machine learning classification algorithms, tuning their parameters, performing feature ablation, presenting the findings in-person, and writing a comprehensive technical report.

---

### 🎯 Key Requirements

1. **Dataset Selection**
   - **Selected Dataset**: **Heart Disease Dataset**
   - Must be a classification dataset.
   - At least **2 classes**.
   - More than **5 features**.
   - Over **200 samples**.
   - Must be a unique dataset per group.

2. **Dataset Description**
   - **Selected Dataset**: **Heart Disease Dataset** with **16 features**:
     1. **Age**
     2. **Gender**
     3. **Blood Pressure**
     4. **Cholesterol Level**
     5. **Smoking**
     6. **Family Heart Disease**
     7. **Diabetes**
     8. **BMI (Body Mass Index)**
     9. **High Blood Pressure**
     10. **High LDL Cholesterol**
     11. **Low HDL Cholesterol**
     12. **Triglyceride Level**
     13. **Fasting Blood Sugar**
     14. **CRP Level**
     15. **Homocysteine Level**
     16. **Heart Disease Status** *(Target Class)*
   - Explain the meaning and importance of the various features.

3. **Data Pre-processing & Cleaning**
   - Clean, handle missing values, encode variables, and scale/normalize as appropriate for ML models.

4. **Classification Approaches**
   - Implement, compare, and evaluate the following classification models (Assigned Members):
     * **A.** Logistic Regression — **Adnan**
     * **B.** Decision Tree — **Isabel**
     * **C.** Random Forest — **Kris** (User)
     * **D.** Stochastic Gradient Descent (SGD) — **Ming-Chi**
     * **E.** Support Vector Machine (SVM) — **Lance**

5. **Hyperparameter Tuning (GridSearchCV)**
   - Use `GridSearchCV` to tune hyper-parameters for each model.
   - Compare tuned vs. baseline model performance.
   - Discuss findings and observations.

6. **Feature Selection & Ablation Study**
   - Randomly or hypothesis-based remove some features.
   - Re-evaluate all classification models with the reduced feature set.
   - Document and analyze how the removal affects model performances.

---

### 📅 Key Milestones & Deliverables

#### 📂 1. Class Presentation
* **Date**: May 26th, 2026 (In-class)
* **Duration**: Maximum 15 minutes per group.
* **Slides**: Recommended no longer than 15 PowerPoint slides.
* **Content**: Presentation of your approach, methodologies, models, and findings.

#### 📝 2. Technical Report & Code Submission
* **Date**: May 31th, 2026 (Before midnight)
* **Written Report**: Maximum 15 pages summarizing all steps (Problem Statement, Preprocessing, Models, Parameter Tuning, Feature Ablation, Findings, Conclusions).
* **Notebook File**: Python notebook with clean code structure, proper headings, and clear explanatory comments.

---

### 🛠️ Execution Checklist for the AI Agent

- [x] **Step 1**: Identify/source a unique classification dataset matching the requirements.
- [x] **Step 2**: Create a Python Jupyter Notebook (`project.ipynb`) or script.
- [x] **Step 3**: Load dataset and document the feature analysis/schema.
- [x] **Step 4**: Implement data cleaning, scaling, and pre-processing.
- [ ] **Step 5**: Train baseline models: Logistic Regression, Decision Tree, Random Forest, SGD, and SVM.
- [ ] **Step 6**: Run `GridSearchCV` on all 5 models to tune hyper-parameters and compile results.
- [ ] **Step 7**: Perform feature ablation (remove features based on importance/hypothesis) and re-evaluate.
- [ ] **Step 8**: Create presentation slides outlining approach, hyperparameter comparison, and feature analysis.
- [ ] **Step 9**: Write the formal technical report summarizing all methodologies and metrics.