# 🌐 Resilient Web App on AWS EC2

This project demonstrates how to deploy and support a Flask-based web application hosted on an Amazon EC2 instance. It simulates a real-world entry-level cloud environment — perfect for showcasing cloud, support, and deployment skills to recruiters.

---

## 🚀 Project Highlights

- ✅ Deployed to AWS EC2 (Amazon Linux 2)
- ✅ Flask backend running on port 5000
- ✅ Secure connection with PEM key and custom security group
- ✅ Architecture diagram included
- ✅ Organized folder structure for real-world projects
- ✅ Project aligns with entry-level AWS Cloud, Tech Support, and Cloud Engineer roles

---
<pre> ## 📁 Folder Structure ``` resilient-webapp-aws/ ├── app/ → Flask app & dependencies │ ├── app.py │ └── requirements.txt ├── templates/ → (Optional) HTML templates ├── support-docs/ → Architecture diagram, deployment notes │ └── resilient-webapp diagram.png └── README.md → Project overview & guide ``` </pre>


---

## 📐 Architecture Diagram

![Architecture](support-docs/resilient-webapp%20diagram.png)



---

## 🧰 Technologies Used

- **AWS EC2** (Amazon Linux 2)
- **Python 3 + Flask**
- **Git Bash / VS Code**
- **Cloudcraft** (for infrastructure diagram)
- **GitHub** (for project documentation and versioning)

---

---

## 🛠️ How to Reproduce This Project

To try this project on your own EC2 instance:

```bash
ssh -i "your-key.pem" ec2-user@<your-public-ip>
cd resilient-webapp-aws/app
pip3 install --user -r requirements.txt
python3 app.py

http://<your-public-ip>:5000/

🎯 Project Status
✅ Live-tested and running on EC2
✅ GitHub folder structure and documentation included
✅ Diagram and deployment flow explained
✅ Ready for recruiters, resumes, and technical portfolios


👨‍💻 About the Author
Wil Rodriguez
Cloud & API Enthusiast | Technical PM | AWS Support Builder

📁 GitHub
🔗 LinkedIn
