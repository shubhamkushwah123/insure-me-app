**Deadline:** You have until Thursday evening, 19th August 2024 7:00 PM CST, to submit the assignment project. It is mandatory to submit this project for completion of the training..

# Project Overview

**Insure Me**, a leading global insurance provider, is transitioning from a monolithic application architecture to a microservice architecture to address various infrastructure and deployment challenges. As part of this transition, they are adopting DevOps practices by implementing a CI/CD pipeline and necessary automations using AWS.

# Objectives

Your primary goals for this project are:

- Deliver frequent product updates to production with high quality and reliability.
- Accelerate software delivery speed and quality.
- Reduce feedback time between developers and testers.

# Current Challenges

- Building complex builds is difficult.
- Manual efforts are required to test various components/modules.
- Incremental builds are difficult to manage, test, and deploy.
- Manual creation and configuration of infrastructure is time-consuming.
- Continuous manual monitoring of the application is challenging.

# Project Requirements

You are required to implement a Proof of Concept (POC) by developing a Mavenized microservice using Spring Boot and an in-memory H2 database with the following endpoints:

### 1. Create Policy

- **Endpoint:** `/createPolicy`
- **HTTP Method:** `POST`
- **Request Body:** JSON

### 2. Update Policy

- **Endpoint:** `/updatePolicy/{policy id}`
- **HTTP Method:** `PUT`
- **Request Body:** JSON

### 3. View Policy

- **Endpoint:** `/viewPolicy/{policy id}`
- **HTTP Method:** `GET`
- **Request Body:** None

### 4. Delete Policy

- **Endpoint:** `/deletePolicy/{policy id}`
- **HTTP Method:** `DELETE`
- **Request Body:** None

# Additional Tasks

- Write necessary JUnit test cases.
- Write necessary Terraform Configuration.
- Configure the test and prod servers using Jenkins pipeline (optional - bonus marks)
- Push the code to your GitHub repository.

# CI/CD Implementation

### Tools and Technologies:

- **Git:** For version control to track changes in the code files.
- **Jenkins:** For continuous integration and continuous deployment.
- **Docker:** For deploying containerized applications.
- **Ansible:** Configuration management tool.
- **Selenium:** For automating tests on the deployed web application.
- **Terraform:** For provisioning of Infrastructure
- **AWS:** For creating EC2 machines as servers and deploying the web application.

### Workflow:

1. Test Server and Prod Server must be configured using Terraform.
2. developer pushes application code to the Git master branch.
3. A Jenkins job is triggered using a GitHub Webhook.
4. The code is checked out, compiled, tested, packaged, containerized, and deployed to test-server automatically using Ansible.
5. Deployment is tested using a test automation tool (Selenium).
6. If the build is successful, it is deployed to the production server using ansible.

All these steps should happen automatically, triggered by a push to the GitHub master branch.

# Application Source Code

The application source code is available at the following link: https://github.com/shubhamkushwah123/insure-me-app.git

# Submission Requirements

- Create a document with detailed step-by-step tasks along with screenshots.
- Mention your GitHub repository containing all the codes, including application code, pipeline code, Dockerfile, Ansible scripts, Terraform scripts, Kubernetes scripts, etc.
- Upload the project in your designated Assignment project acitivity in iON.

We look forward to your innovative and efficient solutions. Good luck!!!
