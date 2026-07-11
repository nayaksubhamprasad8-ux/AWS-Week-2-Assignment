# AWS-Week-2-Assignment
AWS Week 2 Assignment: A responsive personal portfolio website hosted on Amazon S3 using AWS Static Website Hosting.
# AWS Week 2 Assignment – Static Portfolio Website

This project is a **responsive personal portfolio website** developed using **HTML5** and **CSS3** as part of the **AWS Cloud Computing Internship – Week 2 Assignment**. The website is designed as a static website and is deployed using **Amazon S3 Static Website Hosting**.

## 📖 Project Overview

The objective of this assignment was to:

- Build a responsive portfolio website using HTML and CSS.
- Host the website on Amazon S3.
- Configure public access permissions.
- Understand static website hosting on AWS.

The portfolio showcases personal information, technical skills, featured projects, and contact details in a clean and responsive interface.

---

## ✨ Features

- Responsive design for desktop, tablet, and mobile devices
- Sticky navigation bar with smooth scrolling
- Hero section with profile picture
- About Me section
- Skills section
- Featured Projects section
- Resume download button
- Contact information and contact form
- Modern UI using pure CSS
- No JavaScript or external frameworks used

---

## 🛠 Technologies Used

- HTML5
- CSS3
- Google Fonts (Poppins)
- Amazon S3 (Static Website Hosting)
- AWS Cloud Computing

---

## 📁 Project Structure

```
AWS-WEEK2-ASSIGNMENT/
│
├── Portfolio/
│   ├── index.html
│   ├── style.css
│   ├── Subham_Prasad_Nayak_Resume.pdf
│   │
│   └── image/
│       ├── image.png
│       ├── CIVI-X.png
│       ├── HEALTH-IQ.png
│       ├── KFC Nutrition Dashboard.png
│       └── Netflix data visualization.png
│
├── Portfolio Images/
│   ├── portfolio-home.png
│   ├── portfolio-about.png
│   ├── portfolio-skills.png
│   ├── portfolio-project-1.png
│   ├── portfolio-project-2.png
│   ├── portfolio-contact.png
│   ├── portfolio-vscode.png
│   ├── ec2-launch-tutorial.png
│   ├── ec2-overview.png
│   ├── cloudfront-overview.png
│   └── s3-static-website-tutorial.png
│
└── README.md
```

---

## 🚀 Running the Website Locally

1. Clone the repository.

```bash
git clone https://github.com/your-username/aws-week2-portfolio.git
```

2. Open the project folder.

3. Open **index.html** in any web browser.

No installation or dependencies are required.

---

## ☁️ Deploying on Amazon S3

### Step 1

Create an S3 bucket with a globally unique bucket name.

### Step 2

Disable **Block Public Access**.

### Step 3

Upload all project files.

### Step 4

Enable **Static Website Hosting**.

Configure:

- Index document

```
index.html
```

- Error document

```
index.html
```

### Step 5

Attach a bucket policy to allow public read access.

### Step 6

Open the generated S3 Website Endpoint URL to access the deployed website.

--

## 📚 Learning Outcomes

Through this assignment, I learned how to:

- Build a responsive static website using HTML and CSS.
- Organize project files efficiently.
- Host static websites using Amazon S3.
- Configure bucket permissions and static hosting.
- Understand the basics of AWS cloud storage and web hosting.

---

## 📌 Future Improvements

- Add JavaScript for interactive components.
- Integrate a working contact form.
- Deploy using Amazon CloudFront with HTTPS.
- Connect a custom domain using Route 53.
- Improve accessibility and SEO.

---

## 👨‍💻 Author

**Subham Prasad Nayak**

B.S. Computer Science & Data Analytics  
Indian Institute of Technology Patna

**Email:** subhamprasadnayak123@gmail.com

**GitHub:** https://github.com/nayaksubhamprasad8-ux

**LinkedIn:** https://linkedin.com/in/subhamprasadnayak

---

## 📄 License

This project was developed for educational purposes as part of the **AWS Cloud Computing Internship (Week 2 Assignment)**.
