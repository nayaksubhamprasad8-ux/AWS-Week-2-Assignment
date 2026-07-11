# ☁️ AWS Week 2 Assignment – Static Portfolio Website

## 📌 Overview

This repository contains my **Week 2 assignment** for the **AWS Cloud Computing Internship**. The objective of this assignment was to gain practical experience with **AWS Compute and Storage Services**, particularly **Amazon EC2** and **Amazon S3**, by deploying a responsive personal portfolio website.

The assignment focuses on understanding how cloud infrastructure can be used to host static web applications and introduces fundamental AWS services used in modern cloud deployments.

---

# 📚 Week 2 Topics Covered

During Week 2, the following AWS services and concepts were studied:

- Amazon EC2 (Elastic Compute Cloud)
- Launching and managing EC2 instances
- Connecting to EC2 using SSH
- Amazon EBS (Elastic Block Store)
- Creating EBS Snapshots
- Amazon S3
- Bucket Policies
- Static Website Hosting
- AWS CLI Basics

---

# 🎯 Assignment Objectives

The assignment consisted of two hands-on tasks.

## Task 1: Launch and Configure an EC2 Instance

### Objective

Learn how to create and configure a virtual server on AWS.

### Activities Performed

- Created an Ubuntu EC2 instance
- Configured Security Groups
- Connected to the instance using SSH
- Installed a web server (Apache/Nginx)
- Hosted a simple web page

### Skills Learned

- EC2 Instance Management
- Linux Command Line
- SSH Connectivity
- Web Server Configuration

---

## Task 2: Static Website Hosting using Amazon S3

### Objective

Host a responsive static website using Amazon S3.

### Activities Performed

- Created an S3 bucket
- Uploaded HTML, CSS, images, and assets
- Disabled Block Public Access
- Configured Bucket Policy
- Enabled Static Website Hosting
- Tested the deployed website

### Skills Learned

- Amazon S3
- Static Website Hosting
- Bucket Policies
- Public Access Configuration
- Website Deployment

---

# 💼 Mini Project

## Personal Portfolio Website

As part of the assignment, I developed a responsive **Personal Portfolio Website** using HTML and CSS and deployed it on **Amazon S3**.

The website serves as my professional portfolio showcasing my education, technical skills, projects, and contact information.

---

# ✨ Features

- Responsive design
- Sticky navigation bar
- Hero section
- About section
- Skills section
- Featured Projects
- Resume download
- Contact section
- Responsive layout for desktop, tablet, and mobile devices

---

# 🛠 Technologies Used

## Frontend

- HTML5
- CSS3

## Cloud Services

- Amazon S3
- AWS Static Website Hosting

## Tools

- Visual Studio Code
- Git
- GitHub

---

# 📁 Project Structure

```
AWS-WEEK2-ASSIGNMENT
│
├── Portfolio
│   ├── index.html
│   ├── style.css
│   ├── Subham_Prasad_Nayak_Resume.pdf
│   │
│   └── image
│       ├── image.png
│       ├── HEALTH-IQ.png
│       ├── CIVI-X.png
│       ├── KFC Nutrition Dashboard.png
│       └── Netflix data visualization.png
│
├── Portfolio Images
│   ├── portfolio-home.png
│   ├── portfolio-about.png
│   ├── portfolio-skills.png
│   ├── portfolio-project-1.png
│   ├── portfolio-project-2.png
│   ├── portfolio-contact.png
│   ├── portfolio-vscode.png
│   ├── ec2-overview.png
│   ├── ec2-launch-tutorial.png
│   ├── cloudfront-overview.png
│   └── s3-static-website-tutorial.png
│
└── README.md
```

---

# 📄 Portfolio Sections

The website contains the following sections:

- Home
- About Me
- Skills
- Projects
- Contact

---



# ☁️ Deployment on Amazon S3

## Step 1

Create an Amazon S3 Bucket.

---

## Step 2

Disable **Block Public Access**.

---

## Step 3

Upload all website files.

---

## Step 4

Enable **Static Website Hosting**.

Configuration:

```
Index Document:
index.html

Error Document:
index.html
```

---

## Step 5

Attach a Bucket Policy allowing public read access.

---

## Step 6

Open the generated Website Endpoint URL.

The portfolio website is now publicly accessible.

---



# 📖 Learning Outcomes

By completing this assignment, I gained practical experience in:

- Understanding AWS Cloud Computing fundamentals
- Creating and managing EC2 instances
- Connecting to cloud servers using SSH
- Working with Amazon EBS
- Hosting static websites on Amazon S3
- Configuring bucket permissions and policies
- Deploying production-ready static web applications
- Organizing frontend project files
- Using Git and GitHub for version control

---

# 🔮 Future Improvements

- Add JavaScript for interactive components
- Connect contact form with AWS Lambda/API Gateway
- Deploy through Amazon CloudFront for CDN support
- Configure HTTPS using AWS Certificate Manager
- Register a custom domain with Amazon Route 53
- Improve SEO and accessibility

---

# 👨‍💻 Author

**Subham Prasad Nayak**

B.S. Computer Science & Data Analytics  
Indian Institute of Technology Patna

📧 Email: subhamprasadnayak123@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/subham-prasad-nayak-769648378/

💻 GitHub: https://github.com/nayaksubhamprasad8-ux

---

# 📜 License

This project was developed for educational purposes as part of the **AWS Cloud Computing Internship – Week 2 Assignment**.
