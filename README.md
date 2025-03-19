# 🚀 Jenkins CI/CD Pipeline Project

This project demonstrates how to automate the deployment of a web application using **Jenkins**, **AWS EC2**, **Docker**, and **NGINX**. The pipeline provisions an EC2 instance, installs Docker, builds a Docker image from a GitHub repository, and serves it using NGINX.

---

## 📌 **Project Overview**
The Jenkins pipeline automates the following steps:
1. **Provision an EC2 instance** using AWS CLI  
2. **Install Docker** on the EC2 instance  
3. **Clone an HTML project** from a GitHub repository  
4. **Build a Docker image** of the HTML project  
5. **Run the Docker container** using NGINX  

---

## 🔑 **Prerequisites**
### ✅ **Jenkins Plugins:**
- **Pipeline**  
- **SSH Agent**  
- **AWS Credentials**  

### ✅ **Jenkins Credentials:**
1. **AWS Access Key & Secret Key** → For provisioning EC2 instances  
2. **SSH Private Key** → For accessing the EC2 instance remotely  
3. **GitHub Credentials** → For pulling the HTML project from the repository  

**🚀How to Run**
Fork and clone this repository.
Configure the required AWS and GitHub credentials in Jenkins.
Install the necessary Jenkins plugins.
Create a new pipeline job in Jenkins and link it to the Jenkinsfile.
Run the pipeline!

**🎯 Expected Output**
✅ EC2 instance is created successfully.
✅ Docker is installed and configured on EC2.
✅ Docker container is running with the HTML project.
✅ Web app is accessible at http://<EC2-IP>

** Project Status**
✔️ Completed and working successfully

**💡 Learnings**
This project helped me strengthen my skills in:
CI/CD Automation with Jenkins
AWS EC2 provisioning using AWS CLI
Docker containerization
GitHub Integration

**🙌 Contributing**
Feel free to fork the repository, open issues, and submit pull requests.
