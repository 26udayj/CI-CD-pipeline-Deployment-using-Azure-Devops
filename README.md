# CI-CD-pipeline-Deployment-using-Azure-Devops

This project demonstrates how to implement a CI/CD pipeline on Azure DevOps for a simple web application. The application is a Node.js app that is hosted on Azure App Service.

Version Control
The project uses Git for version control. The repository is hosted on GitHub.

Azure DevOps
The CI/CD pipeline is implemented in Azure DevOps. The project is hosted in an Azure DevOps organization.

CI Pipeline
The CI pipeline is triggered on every push to the master branch. The pipeline performs the following steps:

Builds the application using Node.js
Runs unit tests
Publishes the build artifacts to an Azure artifact feed
CD Pipeline
The CD pipeline is triggered when a new release is created in Azure DevOps. The pipeline performs the following steps:

Pulls the latest build artifacts from the Azure artifact feed
Deploys the application to Azure App Service
How to Use
To use this project, you will need to:

Create an Azure DevOps organization and project.
Clone the GitHub repository to your local machine.
Install the Azure DevOps CLI.
Run the following command to create a new release:
az devops release create --project demo


5. The CD pipeline will automatically deploy the application to Azure App Service.

## Further Reading

* [Azure DevOps documentation](https://docs.microsoft.com/en-us/azure/devops/)
* [Git documentation](https://git-scm.com/book/en/v2)
* [Azure App Service documentation](https://docs.microsoft.com/en-us/azure/app-service/)
![image](https://github.com/26udayj/CI-CD-pipeline-Deployment-using-Azure-Devops/assets/90312967/fbf4771a-e4bb-4f06-8bee-37540894c8b7)
