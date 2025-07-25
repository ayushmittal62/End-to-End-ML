# End-to-End ML: Student Performance Prediction

An end-to-end machine learning project for predicting student performance — from data preparation, model training, pipeline orchestration to Dockerization and AWS deployment.

---

## 🔍 Features

- **Data ingestion & preprocessing**  
  Load CSV data, perform cleaning, handle missing values, encode categorical features, and scale numeric variables.

- **Exploratory Data Analysis (EDA)**  
  Visualize patterns and relationships in the dataset.

- **Model training & evaluation**  
  Train ML models, evaluate using metrics, and save the trained pipeline.

- **ML pipeline**  
  Modularized pipeline using Python scripts for better maintainability.

- **Model logging & tracking**  
  Integrated MLflow (or similar) for tracking experiments.

- **Packaging & serving**  
  Flask API exposing endpoints for predictions via HTML forms and JSON.

- **Containerization**  
  Dockerfile for building a containerized ML inference service.

- **CI/CD with GitHub Actions**  
  Automate Docker image building and deployment to AWS EC2 using self-hosted runner.

- **AWS Deployment**  
  Deployed using ECR + EC2, with GitHub Actions and IAM integration.

---

## 🛠️ Project Setup

```bash
git clone https://github.com/ayushmittal62/End-to-End-ML.git
cd End-to-End-ML
pip install -r requirements.txt


## Flow Chart 
<img width="6268" height="2412" alt="diagram" src="https://github.com/user-attachments/assets/dcbc201b-3ebc-45cc-b334-d5684cb84fbb" />
