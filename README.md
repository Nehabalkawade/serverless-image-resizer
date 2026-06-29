# Serverless Image Resizer

## 📌 Project Overview
This project automatically resizes images uploaded to an Amazon S3 bucket using AWS Lambda. When a user uploads an image, an S3 event triggers the Lambda function, which resizes the image and stores it in a destination S3 bucket.

---

## 🎯 Purpose
- Automate image resizing
- Learn event-driven architecture
- Reduce manual effort using AWS serverless services

---

## 🧰 AWS Services Used
- AWS Lambda
- Amazon S3
- AWS IAM
- Amazon CloudWatch

---

## 📂 Project Structure

```
serverless-image-resizer/
│── lambda_function.py
│── requirements.txt
│── README.md
│── architecture.png
└── screenshots/
    ├── source-bucket.png
    ├── destination-bucket.png
    ├── lambda-function.png
    ├── cloudwatch-logs.png
    └── resized-image.png
```

---

## ⚙️ Workflow

1. Upload an image to the Source S3 Bucket.
2. S3 triggers the Lambda function.
3. Lambda resizes the image.
4. The resized image is stored in the Destination S3 Bucket.
5. Logs are available in CloudWatch.

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 👩‍💻 Author

Neha Balkawade
