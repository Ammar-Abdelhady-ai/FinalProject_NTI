
# FinalProject_NTI

This repository contains the code for the **Final Project** as part of the **DevOps & Automation** training at NTI.

## Project Overview

The goal of this project is to implement a solution that integrates the technologies learned throughout the course to solve a real-world problem. This project showcases the implementation of Docker, Kubernetes, Jenkins, CI/CD pipelines, Terraform, and other automation tools.

## Features

- Docker containerization for all services
- Kubernetes deployment for scalability and high availability
- CI/CD pipeline using Jenkins for continuous integration and deployment
- Infrastructure automation using Terraform
- Configuration management with Ansible

## Installation

Follow these steps to set up and run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ammar-Abdelhady-ai/FinalProject_NTI.git
   ```

2. Navigate to the project directory:
   ```bash
   cd FinalProject_NTI
   ```

3. Build the Docker images:
   ```bash
   docker-compose build
   ```

4. Run the application using Docker Compose:
   ```bash
   docker-compose up
   ```

5. Access the application through the web interface:
   Open your browser and go to `http://localhost:8080`

## Technologies Used

- **Docker**: For containerization of the application
- **Kubernetes**: For orchestration and scaling
- **Jenkins**: For CI/CD pipeline automation
- **Terraform**: For infrastructure provisioning and management
- **Ansible**: For configuration management
- **GitHub**: For version control and collaboration

## Project Structure

- `docker-compose.yaml`: Configuration file for Docker Compose
- `Jenkinsfile`: Jenkins pipeline configuration
- `infrastructure/`: Contains Terraform files for provisioning resources
- `ansible/`: Contains Ansible playbooks for configuration management

## Contributing

If you would like to contribute to this project, feel free to open a pull request or submit issues.

1. Fork the repository
2. Create a new branch for your changes
3. Commit your changes and push to your fork
4. Open a pull request with a description of the changes