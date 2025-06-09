
# 🛠️ Mini Project: 5 Essential Skills to Elevate Your Shell Scripting Journey into Cloud Computing

## 📍 Objective

This project focuses on developing a **shell script** that automates the provisioning of AWS EC2 instances and S3 buckets. The goal is to integrate and apply **five core shell scripting concepts** in a practical, cloud-based scenario—preparing you for real-world roles in **Cloud**, **DevOps**, and **System Engineering**.

---

## 🧩 Scenario

**DataWise Solutions**, a data science consulting firm, is supporting a fast-growing e-commerce startup. The client needs a data science workspace deployed quickly and reliably on AWS to analyze customer behavior data.

Their cloud environment must include:

- **EC2 Instances** for compute tasks  
- **S3 Buckets** for storing large customer interaction datasets  

To meet this need, we'll build a **shell script** that automates these tasks using best practices in scripting and AWS automation.

---

## 🧠 My Understanding of the Requirement

This project is about writing a practical shell script to:
- Launch one or more EC2 instances
- Create S3 buckets for data storage
- Accept dynamic input and handle errors

The script must apply five specific shell scripting techniques to simulate a real DevOps task:

### 🔧 1. Functions
Used to modularize the script:
- `create_ec2_instance()`
- `create_s3_bucket()`
- `verify_deployment()`

### 📦 2. Arrays
Arrays will store created resources for easy logging and reference:
```bash
ec2_instances=()
s3_buckets=()
````

### 🔐 3. Environment Variables

Used to secure and configure:

* AWS credentials
* Default region
* Instance type, etc.

### 🧾 4. Command Line Arguments

The script will allow flexible input:

```bash
./deploy.sh t2.micro my-bucket-name
```

### 🚨 5. Error Handling

All AWS CLI interactions will be wrapped in checks to:

* Detect failures
* Log errors
* Recover or exit gracefully

---

## 🚀 Real-World Relevance

This project is a stepping stone toward becoming proficient in:

* **Infrastructure Automation**
* **Cloud Provisioning**
* **Script-based DevOps workflows**

By mastering scripting fundamentals in a cloud context, you're preparing for real tasks in CI/CD pipelines, system provisioning, and environment automation.

---

## ✅ Next Steps

We will:

1. Design the folder structure and script template
2. Build the script incrementally using the 5 concepts
3. Test using AWS CLI in a real or sandbox AWS account
4. Document the full process with screenshots and code comments

---

