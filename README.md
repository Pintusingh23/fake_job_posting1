# fake_job_posting1
**Project:** Fake Job Posting Detection
**Authors:** Pintu Singh (230105), Pranay Sarkar (230047), Fathal (230043)
## Project Overview
This project builds a Machine Learning pipeline to automatically detect fake job postings using structured and unstructured features from job ads (title, description, location, company profile, employment type, etc.). The goal is to classify job postings as **real (0)** or **fake (1)** to help reduce fraud and protect job seekers.
## Problem Statement
How can machine learning techniques be applied to automatically detect and classify fake job postings given the increasing prevalence of online recruitment scams?

---## Dataset
- **Source:** Kaggle — *Fake Job Postings* dataset.  
- **Filename (expected):** `fake_job_postings.csv`  
- **Size:** ~18,000 postings (both real & fake).  
- **Important columns:** `title`, `department`, `company_profile`, `description`, `requirements`, `benefits`, `benefits`, `employment_type`, `required_experience`, `required_education`, `industry`, `function`, `country`, `state`, `city`, `fraudulent` (label: 0 = real, 1 = fake).

Link: https://www.kaggle.com/datasets/shivamb/real-or-fake-job-postings
## Environment & Requirements
- Python 3.10 / 3.11 recommended  
- Key packages:
  - `pandas`, `numpy`
  - `scikit-learn`
  - `xgboost`
  - `nltk`
  - `scipy`
  - `matplotlib`, `seaborn` (for plots)

install requirements using `pip`:
```bash
python3.11 -m venv venv
source venv/bin/activate
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt