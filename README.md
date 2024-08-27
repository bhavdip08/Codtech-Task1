**Name:** Bhavdip Akabari  
**Company:** Codtech It Solutions  
**ID:** CT08DS6150  
**Domain:** DevOps Intern  
**Duration:** Aug To Aug 2024  
**Mentor:** Muzammil Ahmed  

## Overview of the Project

### Project: CI/CD PIPELINE WITH JENKINS

### Objective: 
Set up a continuous integration/continuous deployment (CI/CD) pipeline using
 Jenkins to automate the build, test, and deployment processes. Install and
 configure Jenkins. Create a Jenkins pipeline to build, test, and deploy a simple
 application

### Key Activities: 
- **Step 1: Install and Configure Jenkins on Windows**  
- **Step 2: Create a Simple Web Application**  
- **Step 3: Write a Dockerfile for the Application**  
- **Step 4: Set Up Jenkins Pipeline**
  - 1.	Install Required Jenkins Plugins:
      - o	Go to "Manage Jenkins" > "Manage Plugins".
      - o	Install the following plugins: Docker Pipeline, Git, and Pipeline.
  - 2.	Create a New Jenkins Pipeline Job:
      - o	Go to the Jenkins dashboard and click on “New Item”.
      - o	Enter the name of the pipeline, for example, SimpleFlaskAppPipeline.
      - o	Select “Pipeline” and click “OK”.
  - 3.	Configure the Pipeline:
      - o	Scroll down to the "Pipeline" section and choose "Pipeline script".
      - o	Enter the script from "pipeline.txt"to define the Jenkins Pipeline:x
  - 4.	Save the Pipeline Configuration:
      - o	Click "Save" to save your pipeline configuration.
- **Step 5: Run and Monitor the Pipeline**
  - 1.	Run the Pipeline:
       - o	Go to the Jenkins dashboard.
       - o	Click on your pipeline job (SimpleFlaskAppPipeline).
       - o	Click “Build Now” to run the pipeline.
  - 2.	Monitor the Pipeline Execution:
       - o	Click on the build number in the "Build History" section to view the console output.
       - o	Check each stage to ensure they run successfully.
  - 3.	Access the Running Application:
       - o	If the Run Docker Container stage executes successfully, your Flask application should now be running in a Docker container.
       - o	Open a web browser and go to http://localhost:5000 to see your application in action.

### Technology Used: 
Python  
Docker  
Bash  
Jenkins CiCd  

### Summary:  
By following these steps, you will have installed and configured Jenkins on Windows, created a simple Flask web application, written a Dockerfile to containerize it, and set up a Jenkins pipeline to automate the build, test, and deployment process. This pipeline demonstrates a basic CI/CD setup that you can expand and customize based on your specific needs.
