![Jenkins](https://img.shields.io/badge/Jenkins-CI-blue)
![Python](https://img.shields.io/badge/Python-3.x-green)
![Pipeline](https://img.shields.io/badge/Pipeline-Declarative-orange)

# Jenkins Pipeline Project

## Project Overview

This project demonstrates the implementation of a **Declarative Jenkins Pipeline** for automating the execution of a Python application. It highlights the core concepts of **Pipeline as Code (PaC)** and **Continuous Integration (CI)** using Jenkins and GitHub.

The pipeline automatically checks out the latest source code, verifies the Python runtime, executes the application, and performs post-build actions, providing a simple yet realistic example of a CI workflow.

---

## Technologies Used

* Jenkins
* Git
* GitHub
* Python
* Linux
* Pipeline as Code (PaC)
* CI/CD

---

## Pipeline Workflow

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Jenkins Pipeline
    │
    ├── Checkout
    ├── Verify Python
    ├── Run Application
    └── Post Actions
```

---

## Pipeline Stages

| Stage           | Description                                   |
| --------------- | --------------------------------------------- |
| Checkout        | Retrieves the latest source code from GitHub  |
| Verify Python   | Confirms the Python runtime is available      |
| Run Application | Executes the Python application               |
| Post Actions    | Reports build status and cleans the workspace |

---

## Repository Structure

```text
jenkinsfile-pipeline-project/
│
├── Jenkinsfile
├── pipeline.py
├── .gitignore
└── README.md
```

---

## Key Features

* Declarative Jenkins Pipeline
* Pipeline as Code approach
* Automated Python execution
* GitHub integration
* Workspace cleanup after execution

---

## Learning Outcomes

Through this project, I gained practical experience with:

* Jenkins Pipeline syntax
* Continuous Integration (CI)
* Pipeline as Code principles
* GitHub and Jenkins integration
* Build automation workflows

---

## Future Improvements

- Add automated unit testing
- Build and publish Docker images
- Integrate with Docker Hub or Amazon ECR
- Deploy to AWS EC2 or Kubernetes
- Add email or Slack notifications
