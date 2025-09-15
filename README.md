## Cloud & DevOps Portfolio

Welcome to my personal portfolio website repository! This site is where I showcase the projects I've built, my experience with cloud technologies, and my approach to solving real-world problems using AWS and DevOps practices.  

The website itself is a static site built with HTML, CSS, and JavaScript, hosted on AWS S3 and served globally via CloudFront. To keep things automated and production-ready, I’ve set up GitHub Actions to deploy changes automatically whenever I update the repository.  

---

## Featured Projects

### Multi-Tier Healthcare Appointment Application
This project is a full-stack healthcare appointment system I built to demonstrate scalable, secure web architecture. Patients can book and manage appointments, while the system ensures high availability and data security. I designed it using EC2, RDS, VPC, ALB, Flask, and Python, with an emphasis on best practices like load balancing, database redundancy, and private networking.  

### Cloud Game Leaderboard – Real-Time Multiplayer Stats
For this project, I built a real-time leaderboard for a multiplayer game. Players can submit scores, see live rankings, and track top performers. The app is entirely cloud-hosted and event-driven, showing off my skills with AWS Lambda, API Gateway, DynamoDB, WebSocket API, SNS, CloudWatch, and IAM. This project highlights my ability to design systems that scale efficiently while remaining secure and observable.  

### Real-Time Serverless Contact Form
This is a serverless web app I created to handle form submissions in real time. It leverages AWS Lambda, API Gateway, DynamoDB, SNS, and CloudWatch to capture, notify, and monitor submissions. I implemented least-privilege IAM roles and designed an event-driven architecture to make the system fully automated, reliable, and easy to maintain.  

---

## Technology Stack
My portfolio and projects are built with a mix of cloud and traditional technologies, including:  

- AWS: S3, CloudFront, Lambda, RDS, DynamoDB, CloudWatch, IAM, SNS  
- Programming & Frameworks: Python, Flask, HTML/CSS/JS  
- DevOps & CI/CD: GitHub Actions, Terraform/CloudFormation (for infrastructure as code)  
- Other Tools: Bootstrap for UI, event-driven architecture design, monitoring and logging  

---

## How Deployment Works
The website is set up with CI/CD so that whenever I push changes to the `main` branch:  
1. GitHub Actions automatically syncs the code to the S3 bucket.  
2. CloudFront cache is invalidated, so visitors always see the latest version instantly.  

This setup ensures my portfolio is always up-to-date, reproducible, and follows real-world DevOps practices — the same processes I use in professional projects.  

## Contact
I’m always open to connecting! Reach me via email at [DJT61@pitt.edu](mailto:DJT61@pitt.edu) or through LinkedIn: [Deion Tulcidas](https://www.linkedin.com/in/deion-tulcidas-5a52a6200/).  

---

This README is meant to show what I build, how I build it, and why it matters. Each project reflects hands-on experience with cloud services, security best practices, and automation that mirrors real production environments.
