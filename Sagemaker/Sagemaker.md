## Everything you need to know about Sagemaker for the exam

# Amazon SageMaker (SM) – AWS AIF-C01 Exam Notes

Amazon SageMaker (SM) is AWS's fully managed platform for machine learning (ML) workflows. For AIF-C01, you need to understand the **purpose, use, and workflow role** of key SageMaker features and governance tools.

---

## 1. Core SageMaker Services

### **SageMaker (SM) Overview**
- Managed service for building, training, tuning, and deploying ML models at scale.
- Handles infrastructure, scaling, and integrations.

### **SageMaker Automatic Model Tuning**
- **Purpose:** Hyperparameter optimization (HPO) to improve model performance.
- **How:** Finds the best hyperparameters by running multiple training jobs with different settings.
- **Key Exam Point:** Saves time, increases model accuracy, no need for manual tuning.

### **SageMaker Deployment and Inference**
- **Purpose:** Serve models for predictions.
- **Types:**
  - **Real-time inference:** Deploy models to endpoints for immediate predictions.
  - **Batch inference:** Run predictions on large datasets (offline).
- **Key Exam Point:** Choose real-time for live requests, batch for bulk predictions.

### **SageMaker Studio**
- **Purpose:** Unified, web-based IDE for ML workflows.
- **Key Exam Point:** Single interface for data prep, building, training, tuning, and deploying models.

### **SageMaker Data Wrangler**
- **Purpose:** Simplifies data prep/feature engineering with a visual interface.
- **Key Exam Point:** Import, clean, transform, and analyze data with little/no code.

### **SageMaker Feature Store**
- **Purpose:** Central storage for ML features.
- **Key Exam Point:** Ensures consistency and reusability of features across training and inference.

### **SageMaker Clarify**
- **Purpose:** Bias detection and model explainability.
- **Key Exam Point:** Identifies bias in data/models; explains predictions for human review and compliance.

### **SageMaker Ground Truth**
- **Purpose:** Data labeling for ML.
- **Key Exam Point:** Uses human and ML-assisted workflows to generate high-quality labeled datasets.

---

## 2. SageMaker Governance & MLOps

### **SageMaker Model Cards**
- **Purpose:** Document key facts about models (purpose, intended use, evaluation).
- **Key Exam Point:** Helps track and communicate model details for governance.

### **SageMaker Model Dashboard**
- **Purpose:** Centralized monitoring and management of deployed models.
- **Key Exam Point:** Gives visibility into model status, performance, and usage.

### **SageMaker Model Monitor**
- **Purpose:** Continuously monitors models in production for data drift, bias, and quality.
- **Key Exam Point:** Detects problems early, helps maintain model performance and compliance.

### **SageMaker Model Registry**
- **Purpose:** Catalogs and manages model versions.
- **Key Exam Point:** Tracks lineage, enables controlled promotion from dev to production.

### **SageMaker Pipelines**
- **Purpose:** Automates ML workflows (data prep → train → deploy).
- **Key Exam Point:** Supports CI/CD for ML, ensures reproducibility and automation.

### **SageMaker Role Manager**
- **Purpose:** Simplifies creation and assignment of IAM roles for SM users.
- **Key Exam Point:** Secures and manages access to resources.

### **SageMaker JumpStart**
- **Purpose:** Provides prebuilt solutions, models, and notebooks to jumpstart ML projects.
- **Key Exam Point:** Accelerates adoption with ready-to-use ML assets.

### **SageMaker Canvas**
- **Purpose:** No-code, visual tool for business analysts to build and deploy ML models.
- **Key Exam Point:** Democratizes ML; allows non-coders to create predictive models.

### **MLflow on SageMaker**
- **Purpose:** Open-source ML lifecycle platform, integrated for tracking experiments/models.
- **Key Exam Point:** Enables experiment tracking, reproducibility, and collaboration within SageMaker.

---

## 3. Summary Table

| Tool/Feature          | Purpose / Use Case                            | Exam Point                                    |
|-----------------------|-----------------------------------------------|-----------------------------------------------|
| SM                    | Managed ML lifecycle                          | Build, train, deploy, and manage ML models    |
| SM Studio             | Unified web-based ML IDE                      | All ML steps in one place                     |
| SM Data Wrangler      | Visual data prep and transformation           | Prepares data with minimal coding             |
| SM Feature Store      | Centralized feature storage                   | Reuse, share, and keep features consistent    |
| SM Clarify            | Bias detection & explainability               | Ensures fair, transparent ML                  |
| SM Ground Truth       | Data labeling                                 | Human/ML-assisted annotation                  |
| SM Auto Model Tuning  | Hyperparameter optimization                   | Improves accuracy automatically               |
| SM Deployment/Inference | Real-time/batch predictions                 | Choose based on use case                      |
| SM Model Cards        | Model documentation                           | Governance, transparency                      |
| SM Model Dashboard    | Model monitoring                              | Performance & health at a glance              |
| SM Model Monitor      | Production model quality monitoring           | Detects drift, bias, and quality issues       |
| SM Model Registry     | Model versioning and management               | Track, promote, and manage models             |
| SM Pipelines          | Automate ML workflows                         | Enables MLOps and reproducibility             |
| SM Role Manager       | IAM role management                           | Access/security control                       |
| SM JumpStart          | Prebuilt ML solutions                         | Quick starts for common ML tasks              |
| SM Canvas             | No-code ML tool                               | Business analyst-friendly ML                  |
| MLflow on SM          | Experiment tracking/ML lifecycle management   | Open-source ML tracking integrated with SM    |

---

## Extra Features

### **Network Isolation Mode**
- **Purpose:** Enhances security by preventing training jobs or models from making network calls to the internet or other AWS services.
- **Key Exam Point:** Use for sensitive workloads to restrict network access during training or inference.

### **SageMaker DeepAR Forecasting Algorithm**
- **Purpose:** Built-in algorithm for time series forecasting.
- **Key Exam Point:** Use DeepAR to forecast time series data, such as demand, sales, or resource utilization.

**For the exam:**  
Focus on **what each feature does, its role in the ML lifecycle, and when you’d use it**. You do **not** need to know configuration or code—just understand the workflow and governance concepts.

