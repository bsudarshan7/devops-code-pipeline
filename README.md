# 🚀 AWS CI/CD Pipeline for Static Website Deployment

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![DevOps](https://img.shields.io/badge/DevOps-CI%2FCD-blue)
![CodePipeline](https://img.shields.io/badge/AWS-CodePipeline-yellow)
![CodeBuild](https://img.shields.io/badge/AWS-CodeBuild-green)
![S3](https://img.shields.io/badge/Amazon-S3-red)

## 📌 Project Overview

Built a complete CI/CD pipeline using AWS services to automatically deploy a static portfolio website hosted on Amazon S3.

Whenever code is pushed to GitHub, the deployment process runs automatically without manual intervention.

## 🏗️ Architecture

```text
GitHub
   ↓
AWS CodePipeline
   ↓
AWS CodeBuild
   ↓
Amazon S3
   ↓
Static Website Hosting
```

## ⚙️ AWS Services Used

* 🔹 AWS CodePipeline
* 🔹 AWS CodeBuild
* 🔹 Amazon S3
* 🔹 GitHub

## 📂 Project Files

```text
📁 Repository
 ├── portfolio.html
 ├── buildspec.yml
 └── README.md
```

## 🔄 Workflow

1. Push code to GitHub
2. CodePipeline detects changes
3. CodeBuild executes build process
4. Files are deployed to S3
5. Website updates automatically

## 🎯 What I Learned

✅ CI/CD Fundamentals

✅ GitHub Integration

✅ AWS CodePipeline

✅ AWS CodeBuild

✅ Amazon S3 Deployment

✅ Static Website Hosting

## 🚀 Future Enhancements

* CloudFront CDN
* Custom Domain (Route 53)
* HTTPS (SSL Certificate)
* Automated Testing

---

### 👨‍💻 Author

**Sudarshan Birajdar**

AWS Cloud | DevOps | Python
