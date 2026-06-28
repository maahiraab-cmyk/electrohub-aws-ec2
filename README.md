# 🚀 ElectroHub - AWS EC2 Website Deployment

## 📌 Project Overview

ElectroHub is a responsive landing page designed to showcase modern home appliances with a sleek and professional user interface.

This project was built as part of my cloud learning journey to gain hands-on experience with AWS, Linux, Git, and web deployment.

---

## 🌐 Live Demo

http://3.226.237.75/#

---

## 📷 Project Preview

### Homepage

![Homepage](screenshots/homepage.png)

### Products Section

![Products](screenshots/electrohub.jpg)

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* Ubuntu Linux
* Apache2 Web Server
* Git
* GitHub
* Amazon EC2 (AWS)

---

## ☁️ AWS Services & Networking Components Used
- Amazon EC2
- Amazon VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Groups
- SSH
- Ubuntu Server

---

## 🎯 Key Skills Demonstrated

- AWS EC2 Deployment
- Linux Server Administration
- Apache Web Server Configuration
- SSH Remote Access
- Git Version Control
- GitHub Repository Management
- Static Website Hosting

---

## 📂 Project Structure

```
electrohub-aws-ec2/
│
├── index.html
├── style.css
├── images/
├── screenshots/
└── README.md
```

---

## 🚀 Deployment Steps

1. Launch an Ubuntu EC2 instance.
2. Configure Security Groups (HTTP, HTTPS, SSH).
3. Connect to the instance using SSH.
4. Install Apache2.

```bash
sudo apt update
sudo apt install apache2 -y
```

5. Upload website files to:

```text
/var/www/html
```

6. Restart Apache.

```bash
sudo systemctl restart apache2
```

7. Access the website using the EC2 Public IP.

---

## 💻 Git Commands Used

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <repository-url>
git push -u origin main
```

---

## 📚 What I Learned

* Creating and launching an AWS EC2 instance
* Configuring Security Groups
* Connecting to Linux servers using SSH
* Installing and managing Apache2
* Hosting a static website on AWS
* Using basic Linux terminal commands
* Version control with Git
* Uploading projects to GitHub

---

## 🎯 Future Improvements

* Host using Amazon S3 + CloudFront
* Add a custom domain with Route 53
* Improve responsiveness for mobile devices
* Add product pages
* Enhance animations and UI
* Implement CI/CD using GitHub Actions

---

## 👩‍💻 Author

**Maahiraa Begum**

Aspiring Cloud Engineer | AWS Learner | Web Enthusiast

GitHub: https://github.com/maahiraab-cmyk

LinkedIn: www.linkedin.com/in/maahiraa-begum-376043388

---

Thank you for checking out my project!

I'm continuously learning Cloud Computing and AWS by building hands-on projects. Feedback and suggestions are always welcome.