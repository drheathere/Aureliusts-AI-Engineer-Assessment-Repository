# Aureliusts-AI-Engineer-Assessment-Repository

# 🚀 AI Engineer Skill Assessment

Welcome! This repository contains the **AI Engineer Skill Assessment** designed to evaluate your skills across the entire data science lifecycle—from data exploration to modeling, validation, and effectively communicating insights.

This assessment will help us better understand your technical skills, problem-solving capabilities, business acumen, and communication effectiveness.

---

## 📝 Overview & Instructions:

[Click this link to view the tutorial video](https://drive.google.com/file/d/1oafmjYmrFPkExQdsqW_FU9xnY_f7567V/view?usp=drive_link)

**Step-by-step Guide for Candidates**

### Step 1: Fork & Clone the Repository

* **Fork** this repository to your own GitHub account.
* **Clone** your fork locally:

  ```bash
  git clone https://github.com/<your-username>/Aureliusts-AI-Engineer-Assessment-Repository.git
  ```
* Navigate into the cloned directory:

  ```bash
  cd Aureliusts-AI-Engineer-Assessment-Repository
  ```

### Step 2: Review Assessment Instructions in Jupyter Notebook

* The Jupyter notebook (`AI_Engineer_Skill_Assessment.ipynb`) inside the **notebooks/** folder contains clear instructions and tasks.

### Step 3: Download the Data and Jupyter Notebook

All necessary files are provided within this repository:

```
.
├── data/
│   └── va_claims_synthetic_20000.csv      # Dataset for analysis
├── notebooks/
│   └── AI_Engineer_Skill_Assessment.ipynb # Assessment notebook with instructions
├── models/                                # Save trained model here (.pkl)
└── recording_upload/                      # Upload your presentation recording here
```

### Step 4: Complete the Assessment Tasks

Within the Jupyter notebook, you'll complete the following tasks:

* **Data Exploration & Understanding**

  * Explore and analyze the dataset.
  * Identify insights and business implications.

* **Data Cleaning & Feature Engineering**

  * Handle missing values and outliers.
  * Perform relevant feature engineering.

* **Modeling & Evaluation**

  * Develop predictive machine learning models.
  * Evaluate models thoroughly using metrics including:

    * Accuracy
    * F1 Score
    * Precision and Recall
    * Sensitivity & Specificity
    * ROC/AUC (optional, encouraged)

* **Model Saving & Loading**

  * Serialize your final model using pickle (`.pkl`) and save it clearly within the **models/** folder.
  * Demonstrate clearly in the notebook how the saved `.pkl` model can be re-loaded and used for predictions.

### Step 5: Record & Upload Your Presentation

* Prepare a short video (5–10 minutes) where you clearly discuss:

  * Your methodology, challenges faced, and solutions.
  * Key insights and model performance.
  * Implications for AI engineering and business.
  * Future recommended steps.
* Upload your recording (`.mp4`) into the **recording_upload/** folder.

---

## 🚩 Important Notes (Disclaimer):

* **Code Runability**: All code submitted must run without errors.
* **Package Requirements**: Clearly identify all Python packages and libraries used.

  * You can do this by including either:

    ```python
    !pip install package_name
    ```

    at the top of your notebook, or as commented code:

    ```python
    # !pip install package_name
    ```
* **Package Flexibility**: You may use any Python libraries you find appropriate, provided they are clearly documented, identified, and your solution remains reproducible.

---

## 📂 Submission Checklist:

Make sure you have completed and submitted the following:

| Deliverable                     | Folder              | Status     |
| ------------------------------- | ------------------- | ---------- |
| Completed Jupyter Notebook      | `notebooks/`        | ✅ Required |
| Serialized Model file (`.pkl`)  | `models/`           | ✅ Required |
| Presentation Recording (`.mp4`) | `recording_upload/` | ✅ Required |

---

## 📌 Submission Instructions:

* Push your completed notebook, saved model, and recorded presentation to your forked repository:

  ```bash
  git add .
  git commit -m "Completed AI Engineer Skill Assessment"
  git push origin main
  ```
* Once pushed, submit your assessment by either:

  * Opening a **Pull Request** back into the original repository, **OR**
  * Providing the direct URL of your forked repository to our review team.

---

## 🧾 Evaluation Criteria:

| Category         | Description                                                                       | Weight (%) |
| ---------------- | --------------------------------------------------------------------------------- | ---------- |
| Technical Skills | Quality of exploration, preprocessing, modeling, and evaluation techniques.       | 40%        |
| Problem-Solving  | Ability to handle complex challenges and troubleshoot issues effectively.         | 25%        |
| Communication    | Clarity and effectiveness in explaining decisions, process, and results.          | 20%        |
| Business Acumen  | Insight into the implications of results for real-world scenarios and next steps. | 15%        |

---

## 📩 Contact for Technical Issues:

If you experience any technical difficulties or have questions regarding this assessment, please contact:

* **Operations Manager:** Anika Murray
  📧 [anika@aureliusts.com](mailto:anika@aureliusts.com)

* **Lead Data & Analytics Architect:** Terrence Calistro
  📧 [terrence@aureliusts.com](mailto:terrence@aureliusts.com)

We're here to help!

---

## ⏳ Estimated Time Investment:

* **Expected duration**: Approximately 4–6 hours.

---

## 🙌 Thank You!

Thank you for taking the time to complete the AI Engineer Skill Assessment. We're excited to review your submission and insights. Good luck! 🚀


## 📄 License & Data:

The dataset and materials provided here are intended exclusively for assessment purposes and remain the intellectual property of Aurelius Tech & Talent Solutions.
```
