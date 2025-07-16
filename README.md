# 🎓 ML Projects Repository

Welcome to the **ML Projects** repository! This collection showcases machine learning projects built with modular, production-ready pipelines focusing on data ingestion, transformation, training, and prediction. The primary example here involves student performance prediction using CatBoost.

---

## 📂 Repository Structure

- `.ebextensions/` — AWS Elastic Beanstalk configuration (`python.config`).  
- `artifacts/` — Stored artifacts including:  
  - `data.csv` — Dataset sample.  
  - `model.pkl` — Trained model file.  
  - `preprocessor.pkl` — Preprocessing pipeline.  
  - `train.csv`, `test.csv` — Split datasets.

- `catboost_info/` — CatBoost training logs and metadata files.

- `notebook/` — Jupyter notebooks and related training info:  
  - `1 . EDA STUDENT PERFORMANCE .ipynb` — Exploratory data analysis notebook.  
  - `2. MODEL TRAINING.ipynb` — Model training notebook.  
  - `catboost_info/` — Training logs inside notebooks folder.

- `src/` — Source code for modular pipeline:  
  - `components/` — Core components:  
    - `data_ingestion.py` — Data loading and ingestion.  
    - `data_transformation.py` — Data preprocessing and feature engineering.  
    - `model_trainer.py` — Model training and evaluation.  
  - `pipeline/` — Pipeline management:  
    - `train_pipeline.py` — Orchestrates training workflow.  
    - `predict_pipeline.py` — Orchestrates prediction workflow.  
  - `exception.py` — Custom exceptions.  
  - `logger.py` — Logging setup.  
  - `utils.py` — Helper utilities.

- `templates/` — HTML templates for UI:  
  - `home.html`  
  - `index.html`

- `app.py` / `application.py` — Main application scripts.  
- `README.md` — Project documentation.  
- `requirements.txt` — Python dependencies.  
- `setup.py` — Package setup.

---

## ⚙️ Setup & Installation

Clone the repository:

git clone https://github.com/Aparna-k246/Ml-projects.git  
cd Ml-projects

Create and activate a virtual environment:

python -m venv venv  
source venv/bin/activate   # Linux/macOS  
venv\Scripts\activate      # Windows

Install dependencies:

pip install -r requirements.txt

---

## 🚀 How to Use

- Run `app.py` or `application.py` to launch the application (e.g., web UI or API).  
- Explore notebooks in `notebook/` for detailed EDA and training steps.  
- Use pipeline scripts in `src/pipeline/` to train models or run batch predictions programmatically.

---

## 🌟 Highlights

- Modular and scalable ML pipelines built in Python.  
- End-to-end student performance prediction example using CatBoost.  
- Separation of concerns: clean architecture for ingestion, transformation, training, and prediction.  
- Integrated logging and exception handling for robustness.  
- Ready for deployment with AWS Elastic Beanstalk configs included.

---

## 💼 Recruiter-Friendly Summary

This repository reflects strong skills in building clean, maintainable, and scalable machine learning pipelines suitable for production. It highlights experience with:

- Designing modular ML pipelines from data ingestion to prediction.  
- Applying advanced gradient boosting methods (CatBoost) for real-world datasets.  
- Handling logging, error management, and configuration in Python projects.  
- Preparing projects for cloud deployment using AWS Elastic Beanstalk.

Ideal for ML engineering or data science roles requiring practical end-to-end ML system development.

---

## 📞 Connect with Me

- GitHub: Aparna-k246 (https://github.com/Aparna-k246)  
- LinkedIn: aparna-k (https://www.linkedin.com/in/aparna-k-628005167/)  
- Email: *Add your email here*

---

⭐ If you find this repository useful, please give it a star!

---

Happy modeling! 📊🤖
