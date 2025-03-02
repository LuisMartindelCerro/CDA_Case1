# CDA_Case1

This is an Academic Project from the *02582 Computational Data Analysis* course at Denmark Technical University (DTU).

## Information about the project

The data for this exercise consists of 100 observations (y, x), where:
- **Y** is the response vector.
- **X** is a 100-dimensional feature matrix.
- There are 1000 additional observations, denoted as **x_new**.

Data is presented in the `.csv` files:
- `_case1Data.csv_`
- `_case1Data_Xnew.csv_`

These files can be found on the course page on DTU Learn, under Assignments.

You may use any programming language, such as **R, Python, or MATLAB**. You are free to choose methods to solve the case but must **justify your choices** in the report. Work should be done in groups of no more than two people.

### **Task**
Your objective is to build a **predictive model** for **Y** based on **X**. You should:
- Argue for your choices.
- Assess the quality of the chosen model.
- Provide predictions **ŷ_new**.
- Estimate the **prediction error**.

### **Deliverables**
You must submit **three documents**:
1. **Report** (max 5 pages, PDF format).
2. **Predictions** (`ŷ_new`) in `_predictions_YourStudentNos.csv_`.
3. **Estimated prediction error (RMSE)** in `_estimatedRMSE_YourStudentNos.csv_`.

---

## The Report

Your report must be a **maximum of 5 pages** (PDF format) and use the **provided LaTeX template** (`case1reportTemplate.pdf`) **without modifying the margins or dimensions**.

### **Required Sections**
Your report should include:
- **Model and Methodology**: Describe your model, selection, and validation.
- **Justification**: Explain your model and validation choices.
- **Handling Missing Data**: Describe how you dealt with missing values.
- **Categorical Variables**: Explain how you handled factors in the features.
- **Predictive Performance**: Estimate the model's performance on **x_new**.

### **Root Mean Squared Error (RMSE) Calculation**
The **Root Mean Squared Error (RMSE)** is computed as:

RMSE = sqrt( (1/n) * Σ (yi - ŷi)² )


Since the true values of **y_new** are unknown, you must **estimate RMSE** rather than calculate it directly. Your report should describe your estimation approach.

---

## The Predictions and Estimated Prediction Error

Your files should be submitted to **DTU Inside** as:

- `_predictions_YourStudentNos.csv_` (containing **ŷ_new**).
- `_estimatedRMSE_YourStudentNos.csv_` (containing estimated RMSE).

The expected format is illustrated in:
- `_sample_predictions_YourStudentNo.csv_`
- `_sample_estimatedRMSE_YourStudentNo.csv_`

⚠ **Important:** Do **not** include headers in these files.

Your predictions (**ŷ_new**) will be evaluated by the teachers.
