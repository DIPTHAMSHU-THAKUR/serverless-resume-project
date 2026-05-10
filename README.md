# AWS Cloud-Native Resume Website

## About The Project

This project is my personal cloud-native resume website built completely on AWS using a serverless architecture.

I created this project to improve my practical cloud skills and understand how real-world applications are deployed in production environments. Along with hosting my resume online, the project also includes a live visitor counter powered by AWS backend services.

While building this project, I learned how different AWS services work together, how CDN improves website performance, and how CI/CD pipelines automate deployments.

---

## Architecture Used

- Amazon S3 – Hosts the static resume website
- Amazon CloudFront – Provides CDN and HTTPS delivery
- AWS Lambda – Handles backend visitor counter logic
- Amazon API Gateway – Connects frontend with Lambda
- Amazon DynamoDB – Stores visitor count data
- GitHub Actions – Automates deployment pipeline

---

## Features

- Fully serverless resume website
- Dynamic live visitor counter
- Global website delivery using CloudFront CDN
- HTTPS secure access
- Automated deployment using GitHub Actions
- Automatic CloudFront cache invalidation
- Cost-efficient cloud architecture
- No traditional servers used

---

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### AWS Services
- Amazon S3
- Amazon CloudFront
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB

### DevOps Tools
- GitHub Actions

---

## CI/CD Automation

I implemented a CI/CD pipeline using GitHub Actions.

Whenever I push changes to GitHub:
1. GitHub Actions automatically starts
2. Updated files are deployed to Amazon S3
3. CloudFront cache gets refreshed automatically
4. Latest version of the website becomes live

This helped me understand real DevOps deployment workflows used in industry environments.

---

## How The Project Works

1. User opens the website
2. CloudFront delivers content from nearest edge location
3. Website loads securely over HTTPS
4. JavaScript sends request to API Gateway
5. API Gateway triggers Lambda function
6. Lambda updates and retrieves visitor count from DynamoDB
7. Updated visitor count is displayed on the website in real time

---

## Visitor Counter Workflow

- Frontend JavaScript sends API request
- API Gateway triggers Lambda function
- Lambda updates visitor count in DynamoDB
- Latest count is returned to frontend
- Visitor count updates dynamically on page load

---

## Security & Optimization

- Implemented HTTPS using CloudFront
- Configured secure S3 bucket access using Origin Access Control (OAC)
- Added CDN caching for faster performance
- Automated deployment workflow using GitHub Actions

---

## What I Learned

Through this project, I learned:

- Serverless architecture
- API integration
- AWS service configuration
- CDN and caching concepts
- HTTPS and secure delivery
- CI/CD automation
- GitHub Actions workflows
- Cloud deployment process
- Debugging cloud infrastructure
- Secure S3 access using OAC
- Building dynamic backend functionality using Lambda and DynamoDB

---

## Live Website

Hosted on AWS using:
- Amazon S3
- Amazon CloudFront

---

## Author

Dipthamshu Thakur  
Aspiring Cloud & DevOps Engineer
