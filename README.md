You will have till till Thursday evening 7:00 PM IST to attempt this project and see how far you can go with this project. Mentor will demo this Capstone project from scratch to the End on Thursday. Please make sure that you do attend Thursday session. Your next session would be on Thursday.

Project Overview:

Insure Me, a leading global insurance provider, is transitioning from a monolithic application architecture to a microservice architecture to address various infrastructure and deployment challenges. As part of this transition, they are adopting DevOps practices by implementing a CI/CD pipeline and necessary automations using AWS.

Objectives:

Your primary goals for this project are:

Deliver frequent product updates to production with high quality and reliability.
Accelerate software delivery speed and quality.
Reduce feedback time between developers and testers.
Current Challenges:

Building complex builds is difficult.
Manual efforts are required to test various components/modules.
Incremental builds are difficult to manage, test, and deploy.
Manual creation and configuration of infrastructure is time-consuming.
Continuous manual monitoring of the application is challenging.
Project Requirements:

You are required to implement a Proof of Concept (POC) by developing a Mavenized microservice using Spring Boot and an in-memory H2 database with the following endpoints:

Create Policy

Endpoint: /createPolicy
HTTP Method: POST
Request Body: JSON
Update Policy

Endpoint: /updatePolicy/{policy id}
HTTP Method: PUT
Request Body: JSON
View Policy

Endpoint: /viewPolicy/{policy id}
HTTP Method: GET
Request Body: None
Delete Policy

Endpoint: /deletePolicy/{policy id}
HTTP Method: DELETE
Request Body: None
Additional Tasks:

Write necessary JUnit test cases.
Generate HTML reports using TestNG.
Push the code to your GitHub repository.
Preload some data into the database.
CI/CD Implementation:

Tools and Technologies:

Git: For version control to track changes in the code files.
Jenkins: For continuous integration and continuous deployment.
Docker: For deploying containerized applications.
Ansible: Configuration management tool.
Selenium: For automating tests on the deployed web application.
AWS: For creating EC2 machines as servers and deploying the web application.
Workflow:

A developer pushes updated code to the Git master branch.
A Jenkins job is triggered using a GitHub Webhook.
The code is checked out, compiled, tested, packaged, containerized, and deployed to a preconfigured test-server automatically.
Deployment is tested using a test automation tool (Selenium).
If the build is successful, it is deployed to the production server.
All these steps should happen automatically, triggered by a push to the GitHub master branch.
Application Source Code:

The application source code is available at the following link: Insure Me Application Source Code

Submission Requirements:

Create a document with detailed step-by-step tasks along with screenshots.
Mention your GitHub repository containing all the codes including application code, pipeline code, Dockerfile, Ansible scripts, Terraform scripts, Kubernetes scripts, etc.
Upload the project in your Designated Google Drive Folder.
We look forward to your innovative and efficient solutions. Good luck!
