# 📊 Employee Attrition Prediction using Machine Learning

> Predicting employee turnover and identifying retention drivers using Python and Logistic Regression

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🎯 Project Overview

Built an end-to-end machine learning solution to predict employee attrition and provide actionable retention strategies for HR leadership.

**Key Achievement:** Model identifies 75% of at-risk employees, enabling proactive retention interventions projected to save $2-3M annually.

---

## 📊 Dataset

- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Size:** 1,470 employees, 35 features
- **Target:** Binary classification (Stayed/Left)
- **Features:** Demographics, compensation, satisfaction, performance, work conditions

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn (Logistic Regression)
- **Environment:** Google Colab

---

## 🔍 Key Findings

### Attrition Drivers Identified:

1. **Overtime Effect:** 30.5% attrition vs 10.4% (3x higher risk!)
2. **Compensation Gap:** Departing employees earn $20,592 less annually
3. **Department Impact:** Sales department shows 20.6% attrition (highest)
4. **Tenure Vulnerability:** 0-2 years is most critical period
5. **Work-Life Balance:** Poor balance significantly increases turnover

---

## 📈 Model Performance

| Metric | Score | Interpretation |
|--------|-------|----------------|
| **Accuracy** | 72.4% | Overall correct predictions |
| **Recall** | 74.5% | Catches 3 out of 4 departures |
| **Precision** | 33.7% | Trade-off for high recall |
| **ROC-AUC** | 0.801 | Good discriminative ability |

**Model Choice Rationale:** Prioritized recall over precision because missing an employee departure ($100K+ cost) is more expensive than false alarms (~$10K intervention cost).

---

## 💡 Business Impact

### Projected Outcomes:
- ✅ Reduce attrition by 4-5 percentage points (from 16% to 11-12%)
- ✅ Retain 60+ employees annually
- ✅ Save $2-3M in recruitment and training costs
- ✅ Achieve 300-400% ROI on retention programs

### Actionable Recommendations:
1. **Overtime Management:** Reduce through strategic hiring in high-risk departments
2. **Compensation Review:** Market benchmarking and targeted adjustments
3. **Onboarding Enhancement:** 90-day structured program with mentorship
4. **Sales Department Focus:** Targeted retention task force
5. **Proactive Monitoring:** Risk scoring system for early intervention

---

## 📁 Project Structure
```
├── HR_Attrition_Analysis.ipynb    # Main analysis notebook
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── visualizations/                 # 11 charts
├── outputs/                        # Model results and summaries
└── README.md
```

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Click the Colab badge: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](link-to-your-notebook)
2. Run cells sequentially
3. All outputs will generate automatically

### Option 2: Local Environment
```bash
# Clone repository
git clone https://github.com/yourusername/employee-attrition-prediction.git
cd employee-attrition-prediction

# Install requirements
pip install pandas numpy matplotlib seaborn scikit-learn

# Run Jupyter Notebook
jupyter notebook HR_Attrition_Analysis.ipynb
```

---

## 📊 Visualizations Preview

### Key Charts:

<img src="visualizations/3_attrition_by_overtime.png" width="400">
<img src="visualizations/7_income_comparison.png" width="400">
<img src="visualizations/feature_importance.png" width="400">

---

## 🎓 Skills Demonstrated

- ✅ End-to-end ML pipeline development
- ✅ Exploratory Data Analysis (EDA)
- ✅ Feature Engineering & Selection
- ✅ Model training, evaluation, and interpretation
- ✅ Data Visualization & Storytelling
- ✅ Business communication (technical → non-technical)
- ✅ ROI analysis and strategic recommendations

---

## 📧 Contact

**[Your Name]**  
📧 your.email@example.com  
💼 [LinkedIn](your-linkedin-url)  
🌐 [Portfolio](your-portfolio-url)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Dataset: IBM HR Analytics (available on Kaggle)
- Tools: Python, Scikit-learn, Google Colab
- Inspiration: Real-world HR analytics challenges

---

⭐ **If you found this project helpful, please star this repository!** ⭐
```

---

### **STEP 4: Create GitHub Account (if you don't have one)**

1. Go to https://github.com
2. Click "Sign Up"
3. Choose username (use professional name: firstname-lastname or firstname_lastname)
4. Complete registration

---

### **STEP 5: Create New Repository**

1. Click **"+"** (top right) → **"New repository"**
2. Fill in details:
   - **Repository name:** `employee-attrition-prediction`
   - **Description:** "ML project predicting employee turnover with 74.5% recall and $2-3M projected savings"
   - **Public** (so recruiters can see it)
   - ✅ Check "Add a README file" (then replace with yours)
   - Choose License: MIT
3. Click **"Create repository"**

---

### **STEP 6: Upload Files**

#### **Method A: Drag & Drop (Easiest)**

1. In your new repo, click **"Add file"** → **"Upload files"**
2. Drag all files from your folder
3. Add commit message: "Initial commit: Complete attrition prediction project"
4. Click **"Commit changes"**

#### **Method B: GitHub Desktop (Recommended if you'll update often)**

1. Download GitHub Desktop: https://desktop.github.com
2. Clone your repository
3. Copy all project files to the cloned folder
4. Commit and push changes

---

### **STEP 7: Add to Resume & LinkedIn**

**Resume:**
```
Employee Attrition Prediction | Python, Scikit-learn, Pandas
- Built ML model (74.5% recall, 0.801 AUC) predicting employee turnover
- Identified overtime and compensation as top drivers through EDA
- Generated recommendations to save $2-3M annually
📂 GitHub: github.com/yourname/employee-attrition-prediction