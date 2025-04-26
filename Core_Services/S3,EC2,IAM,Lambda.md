# AWS Core Services for AIF-C01 Exam: IAM, S3, EC2, Lambda

This guide summarizes what you need to know about IAM, S3, EC2, and Lambda for the AWS Certified AI Practitioner (AIF-C01) exam.  
**Focus: Concepts only – no hands-on setup, configuration, or coding required.**

---

## 1. AWS Identity and Access Management (IAM)

- **Purpose:** Controls who can access AWS resources and what they can do.
- **Key Concepts:**
  - **Users, Groups, Roles:** Ways to define and organize access.
  - **Policies:** Rules that say what actions are allowed or denied.
- **For the Exam:**  
  - Know that IAM is used for security and permissions.
  - Understand that IAM roles and policies are used by AWS services (like SageMaker) to control access.
  - You do **NOT** need to know how to create users, groups, or policies.

---

## 2. Amazon S3 (Simple Storage Service)

- **Purpose:** Object storage service in AWS.
- **Key Concepts:**
  - **Buckets:** Containers for storing data.
  - **Objects:** The actual files/data you upload (e.g., datasets, models).
- **For the Exam:**  
  - S3 is used to store datasets and model files for ML/AI workflows.
  - Just know S3 = main AWS storage for data.
  - You do **NOT** need to know about storage classes, lifecycle rules, or advanced features.

---

## 3. Amazon EC2 (Elastic Compute Cloud)

- **Purpose:** Provides scalable virtual servers (compute power) in the cloud.
- **Key Concepts:**
  - EC2 runs applications and workloads, including ML model training and inference.
- **For the Exam:**  
  - Understand EC2 is where computation happens behind the scenes (e.g., for SageMaker or other ML services).
  - You do **NOT** need to know how to launch/configure EC2 instances or know any instance types.

---

## 4. AWS Lambda

- **Purpose:** Serverless compute – run your code automatically in response to events, no servers to manage.
- **Key Concepts:**
  - Event-driven: Code runs when triggered by something (e.g., file upload, API call).
- **For the Exam:**  
  - Lambda can be used to automate ML workflows (e.g., process data when uploaded).
  - You do **NOT** need to know how to set up or configure Lambda functions.

---

## **Summary Table**

| Service | What to Know for the Exam                             |
|---------|------------------------------------------------------|
| IAM     | Manages access/permissions for AWS resources         |
| S3      | Stores data (buckets & objects) for ML workflows     |
| EC2     | Provides compute power for ML/AI tasks               |
| Lambda  | Runs code automatically in response to events        |

---

**That’s it!**  
For the AIF-C01 exam, focus on **what these services do** and **their basic role in AI/ML workflows**.  
No need for setup, hands-on, or advanced features.

