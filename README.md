# 📦 Upload Jenkins Logs to S3

This project demonstrates how to **upload Jenkins build logs to an AWS S3 bucket** using a shell script. It automates the collection of logs generated during Jenkins jobs and transfers them to Amazon S3 for centralized storage, backup, or further analysis.

The shell script scans the Jenkins logs directory, filters based on the current date (or custom logic), and securely uploads relevant logs using the AWS CLI.

---

## 🔑 Key Features

- 🖥️ **Shell script automation** for collecting and uploading logs
- ☁️ **AWS S3 integration** using AWS CLI
- 📆 **Date-based filtering** of Jenkins log files
- 🔄 **Daily or scheduled uploads** using `cron` or Jenkins post-build steps
- 🔌 **Easy integration** into any CI/CD pipeline

---

## 📽️ Demo Video

Watch a step-by-step walkthrough of the script in action:

➡️ [Watch the Video] https://drive.google.com/file/d/1XdN4WerqgpDjVihjtI7vNm0BfkoGPvSC/view?usp=sharing

---

## 📄 Standard Operating Procedure (SOP)

Complete setup, configuration, and usage guide:

➡️ [Read the SOP] https://docs.google.com/document/d/1kKF_NZak7sZ4rvPz1NQPgrHSUEDN3yJUefO9692zC50/edit?usp=sharing

---
