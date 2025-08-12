# Jenkins + Flask CI/CD Pipeline

This is a beginner-friendly **DevOps project** that demonstrates how to set up a **Continuous Integration and Continuous Deployment (CI/CD)** pipeline using **Jenkins** for a simple Python Flask application.

---

## Project Overview
- **Language**: Python (Flask)
- **CI/CD Tool**: Jenkins
- **Testing Framework**: Pytest
- **Version Control**: GitHub

This project automatically:
1. Pulls code from GitHub.
2. Installs dependencies.
3. Runs automated unit tests.
4. Deploys the Flask app.

---


---

Getting Started

Clone the repository
bash
git clone https://github.com/<YOUR_USERNAME>/jenkins-flask-ci-cd.git
cd jenkins-flask-ci-cd

Install dependencies
pip install -r requirements.txt

 Run locally
python app.py


Jenkins Pipeline Stages

Clone Repository – Pulls latest code from GitHub.
Install Dependencies – Installs required Python packages.
Run Tests – Executes unit tests using Pytest.
Deploy – Runs the Flask app on the server.


 Running Tests
pytest

 Sample Output
================ test session starts ================
collected 1 item

test_app.py .                                      [100%]
================= 1 passed in 0.12s =================


Skills Demonstrated

Git & GitHub
Jenkins CI/CD
Python Flask Development
Automated Testing (Pytest)
Deployment Automation

