# Unlabelled Data – AWS AIF-C01 Notes

## What is Unlabelled Data?
- Data that has **inputs only**, with no known outputs or target values.
- Used in **unsupervised learning** and **self-supervised learning**.

## Examples
- Customer browsing history with no known intent.
- Sensor data without outcome labels.

## Use Cases
- Discovering hidden patterns or groupings (clustering).
- Pre-training models with self-supervised learning (e.g. masked word prediction).

## AWS Context
- Used in training foundation models and running unsupervised learning tasks in SageMaker.
- Can be labelled later using Amazon SageMaker Ground Truth if needed.

## Tip for Exam
- Know the difference between **labelled (supervised)** and **unlabelled (unsupervised/self-supervised)** data.
