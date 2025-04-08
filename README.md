 Set-up-a-Jenkins-CI-CD-pipeline-to-build-and-deploy-a-sample-application-using-Docker.

 my-ci-cd-project/
├── app.py (or index.html, main.js etc.)
├── Dockerfile
├── Jenkinsfile
├── requirements.txt
└── README.md

Steps to Execute the Task
1. Install Jenkins
On Windows:
Download Jenkins from https://www.jenkins.io/download/
Install it and run Jenkins (usually at http://localhost:8080)

2. Install Required Plugins
Go to Manage Jenkins > Plugins.
Install:
Git Plugin
Pipeline
Docker Pipeline (optional)

3. Create Your Sample App
4. Create a Dockerfile
5. Create requirements.txt
6. Create the Jenkinsfile
7. Push Your Code to GitHub
8. Configure Jenkins Job
9. Trigger the Pipeline
    Make a small change in code and push again to GitHub.
    Jenkins should automatically start the pipeline if webhooks are set up.
    Or you can manually build from Jenkins UI.
