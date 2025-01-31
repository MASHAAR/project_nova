Nova Web Application DevOps Project
Overview
This project demonstrates various DevOps principles, including version control, containerization, infrastructure as code (IaC), CI/CD pipeline creation, and Site Reliability Engineering (SRE). The task simulates real-world practices by setting up and deploying a web application while focusing on automation, monitoring, and ensuring system reliability.

Project Breakdown
Task 1: Version Control Integration
Objective: Created a Git repository for a sample web application.
Key Actions:
Set up a Git repository.
Made meaningful commits with clear messages.
Pushed the repository to a remote Git server (GitHub).
Task 2: Containerization with Docker
Objective: Containerized the web application.
Key Actions:
Created a Dockerfile for the web application.
Used Docker Compose to simulate a multi-container environment (application + database).
Exposed necessary ports and ensured dependencies were included.
Task 3: Infrastructure as Code (IaC)
Objective: Defined and deployed cloud resources using CloudFormation.
Key Actions:
Created a virtual machine instance with security configurations.
Set up networking components, including VPC and subnets.
Deployed cloud resources successfully using IaC.
Task 4: CI/CD Pipeline with Cloud Integration
Objective: Built and deployed the web application using a CI/CD pipeline.
Key Actions:
Created a CI/CD pipeline using CircleCI.
Built, tagged, and pushed the Docker image to a container registry (Docker Hub).
Deployed the application to a cloud-based environment (EC2 instance).
Task 5: Site Reliability Engineering (SRE)
Objective: Implemented SRE principles for monitoring and ensuring the reliability of the deployed application.
Key Actions:
Set up monitoring tools: Prometheus and Grafana.
Configured alerts for critical metrics.
Implemented basic incident response procedures.
Setup Instructions
Clone the repository:

bash
Copy
Edit
git clone https://github.com/username/nova-app.git
Build and start containers using Docker Compose:

bash
Copy
Edit
docker-compose up --build
Access the web application:

Navigate to http://localhost:8080 to view the app.
Monitor the application:

Prometheus: http://localhost:9090
Grafana: http://localhost:3000
Technologies Used
Docker
Git
CircleCI
AWS CloudFormation
Prometheus, Grafana
Postgres (Database)
