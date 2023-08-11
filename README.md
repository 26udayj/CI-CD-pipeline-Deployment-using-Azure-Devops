# CI-CD-pipeline-Deployment-using-Azure-Devops
![Screenshot 2023-08-11 142652](https://github.com/26udayj/CI-CD-pipeline-Deployment-using-Azure-Devops/assets/90312967/9af298ae-c478-4e03-bb8c-14914d254346)
![Screenshot 2023-08-11 142715](https://github.com/26udayj/CI-CD-pipeline-Deployment-using-Azure-Devops/assets/90312967/5c2caeb6-e327-4eff-83c2-cd2e1f5aca6b)
![Screenshot 2023-08-11 142728](https://github.com/26udayj/CI-CD-pipeline-Deployment-using-Azure-Devops/assets/90312967/9d3f8346-d9b5-4cbc-916d-a8b86706ab31)
![Screenshot 2023-08-11 142752](https://github.com/26udayj/CI-CD-pipeline-Deployment-using-Azure-Devops/assets/90312967/3dcabd57-08d7-4261-8093-247a415a36e5)

This project demonstrates how to implement a CI/CD pipeline on Azure DevOps for a simple web application. The application is a C# app that uses .NET 3.5 and is hosted on Azure App Service.


Version Control
The project uses Git for version control. The repository is hosted on GitHub.

Azure DevOps
The CI/CD pipeline is implemented in Azure DevOps. The project is hosted in an Azure DevOps organization.

CI Pipeline
The CI pipeline is triggered on every push to the master branch. The pipeline performs the following steps:

Builds the application using .NET 3.5
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

The CD pipeline will automatically deploy the application to Azure App Service.


Note: .NET 3.5 is a legacy version of the .NET Framework and is no longer supported by Microsoft. If you are planning to use this project in production, you should consider using a newer version of the .NET Framework.

## Further Reading

* [Azure DevOps documentation](https://docs.microsoft.com/en-us/azure/devops/)
* [Git documentation](https://git-scm.com/book/en/v2)
* [Azure App Service documentation](https://docs.microsoft.com/en-us/azure/app-service/)
