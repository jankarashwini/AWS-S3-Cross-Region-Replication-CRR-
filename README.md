# ☁️ AWS S3 Cross-Region Replication (CRR)

## 📌 Project Overview

This project demonstrates how to configure Amazon S3 Cross-Region Replication (CRR) to automatically replicate objects from a source S3 bucket in one AWS Region to a destination bucket in another AWS Region.

The project focuses on S3 bucket configuration, versioning, replication rules, IAM permissions, and verifying object replication across AWS Regions.<img width="940" height="657" alt="image" src="https://github.com/user-attachments/assets/a75da62c-23c7-49ab-9c12-7339262213a8" />







## 🎯 Project Objectives

- Configure S3 buckets in two different AWS Regions.
- Enable versioning on source and destination buckets.
- Set up Cross-Region Replication (CRR).
- Configure the required IAM role and permissions.
- Verify that new objects are replicated to the destination bucket.
- Understand how cross-region replication supports data availability and disaster recovery.

## 🛠️ Technologies Used

- ☁️ Amazon Web Services (AWS)
- 🪣 Amazon S3
- 🔄 S3 Cross-Region Replication (CRR)
- 🔐 AWS IAM
- 🌍 AWS Regions

## 🏗️ Project Architecture

**Source S3 Bucket — Mumbai (`ap-south-1`)**

⬇️

**S3 Replication Rule + IAM Role**

⬇️

**Destination S3 Bucket — N. Virginia (`us-east-1`)**

When an eligible object is uploaded to the source bucket, Amazon S3 replicates it to the destination bucket according to the configured replication rule.

## ✨ Key Features

- 🪣 S3 Bucket Configuration
- 🌍 Cross-Region Data Replication
- 🔄 Automated Object Replication
- 🗂️ Bucket Versioning
- 🔐 IAM Roles and Permissions
- 🛡️ Improved Data Availability
- ♻️ Disaster Recovery Support
- ✅ Replication Status Verification

## ⚙️ Implementation Steps

1. Created a source S3 bucket in the Mumbai Region (`ap-south-1`).
2. Created a destination S3 bucket in the N. Virginia Region (`us-east-1`).
3. Enabled bucket versioning on both buckets.
4. Created a replication rule on the source bucket.
5. Configured the destination bucket and required IAM replication permissions.
6. Uploaded a test file to the source bucket.
7. Verified that the object was replicated to the destination bucket.


## 📈 Project Outcome

Configured Amazon S3 Cross-Region Replication between buckets in two AWS Regions to demonstrate automatic replication of eligible objects and improve cross-region data availability.

## 📚 Key Learnings

- Amazon S3 bucket management
- AWS Region selection
- S3 bucket versionin
- Cross-Region Replication configuration
- IAM roles and permissions
- Object replication verification
- Data availability and disaster recovery concepts

## 🏁 Conclusion

This project provided hands-on experience with Amazon S3 Cross-Region Replication and demonstrated how objects can be replicated across AWS Regions to support data protection and disaster recovery strategies.

## 👩‍💻 Author

**Ashwini Jankar**

Cloud & DevOps Learning Projects
