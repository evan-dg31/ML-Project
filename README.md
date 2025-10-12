## End to End Machine Learning Project
This repository demonstrates a complete end-to-end Machine Learning workflow, from raw data ingestion to model deployment on AWS. It follows production-grade standards including modular project structure, logging, exception handling, CI/CD readiness, and scalable cloud deployment using AWS Elastic Beanstalk, EC2, and ECR.

### Project Overview
---
1. This project aims to showcase a real-world ML system that automates the following pipeline:

2. Data Ingestion → Reading raw data from a source (CSV, database, or S3).

3. Data Transformation → Preprocessing using Pipelines (feature engineering, encoding, scaling).

4. Model Training → Training multiple models and selecting the best-performing one.

5. Hyperparameter Tuning → Using GridSearchCV or RandomizedSearchCV for optimization.

6. Model Evaluation & Saving → Storing the best model as a serialized artifact (.pkl).

7. Prediction Pipeline → Serving predictions using the trained model.

8. Deployment on AWS → Packaging and deploying via Elastic Beanstalk, EC2, and ECR.
