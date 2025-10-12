# IBM DevOps Capstone Project

## 🧾 About This Project

This repository showcases the final capstone project from the **IBM DevOps and Software Engineering Professional Certificate**, completed as part of my applied DevOps training. The project simulates a real-world microservice lifecycle—from design and development to testing, deployment, and monitoring—using industry-standard tools and methodologies.

## 🚀 Project Objectives

- Build a secure, cloud-native microservice using Flask and Python
- Apply Test-Driven Development (TDD) to achieve >95% code coverage
- Implement CI/CD pipelines with Azure DevOps, Helm, and ArgoCD
- Enforce code quality standards via SonarQube integration
- Deploy containerized services to Kubernetes clusters
- Enhance observability with Prometheus and Grafana dashboards

## 🧰 Tech Stack

- **Languages**: Python, Shell
- **Frameworks**: Flask (RESTful API)
- **CI/CD**: Azure DevOps, Helm, ArgoCD
- **Monitoring**: Prometheus, Grafana
- **Code Quality**: SonarQube
- **Containerization**: Docker, Kubernetes
- **Testing**: Pytest, TDD methodology

## 📦 Project Structure

```text
├── service/             # Microservice code (MVC pattern)
│   ├── models.py        # Business logic and data model
│   ├── routes.py        # RESTful API endpoints
│   └── config.py        # Flask configuration
├── tests/               # Unit and integration tests
│   ├── test_models.py
│   ├── test_routes.py
│   └── factories.py
├── deploy/              # Kubernetes manifests and Helm charts
├── .github/             # CI/CD workflows
├── bin/                 # Setup and environment scripts

```

## 📊 Data Model

The microservice manages user accounts with the following fields:

| Field         | Type         | Required |
|---------------|--------------|----------|
| `id`          | Integer      | Yes      |
| `name`        | String(64)   | Yes      |
| `email`       | String(64)   | Yes      |
| `address`     | String(256)  | Yes      |
| `phone_number`| String(32)   | No       |
| `date_joined` | Date         | Yes      |

## 🧪 How to Run Locally

1. Clone the repository  
2. Source the setup script:  
   ```bash
   source bin/setup.sh
3. Activate the Python virtual environment
4. Run tests:
   ```bash
    make test
5. Start the service locally or deploy to Kubernetes


## 🧑‍💻 Author
[William Mayila](https://www.linkedin.com/in/william-mayila) |DevOps Engineer | Cloud-native infrastructure & CI/CD automation | Bilingual (EN/FR)
