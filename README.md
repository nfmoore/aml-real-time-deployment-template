# AML Real-Time Scoring Deployment Template

[![Build Status](https://dev.azure.com/nfmoore-projects/AML%20Deployment%20Templates/_apis/build/status/nfmoore.aml-real-time-deployment-template?branchName=master)](https://dev.azure.com/nfmoore-projects/AML%20Deployment%20Templates/_build/latest?definitionId=12&branchName=master)

Machine Learning Operations (MLOps) is based on DevOps principles and practices that increase the efficiency of Machine Learning workflows. It aims to facilitate faster experimentation, development and production deployment of Machine Learning models while ensuring high quality standards. A standard end-to-end MLOps workflow will consist of model training, registration, deployment and monitoring.

This deployment template uses [Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-ml) and [Azure Pipelines](https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines) (part of Azure DevOps). The template contains code and DevOps pipeline definitions to automated end-to-end deployment of machine learning models as a web service for real-time inferencing using MLOps principles and practices. The template includes: unit tests and code coverage, model training and registration, controlled deployments (via approvals) to a test environment and production environment using AKS, endpoint [monitoring](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-enable-app-insights), [endpoint data collection](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-enable-data-collection) and [data drift detection](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-monitor-datasets).

## Prerequisites

- Azure subscription (contributor or owner)
- Azure DevOps project
- GitHub account

## Getting Started

Follow the instructions in the [getting started](docs/getting_started.md) doc to deploy this solution in your own Azure subscription. You can find the details of the files and folders in the repository [here](/docs/repository_details.md).

Note: the dataset used in this deployment template is the [Cardiovascular Disease dataset](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset) available on Kaggle.

## Related Projects

Check out these related projects:

- [AML Platform Deployment Template](https://github.com/nfmoore/aml-platform-deployment-template) - automated deployment of a machine learning platform using Azure DevOps
- [AML Batch Scoring Deployment Template](https://github.com/nfmoore/aml-batch-deployment-template) - automated end-to-end deployment of machine learning models as an AML Pipeline for batch inferencing

## References

- [Azure Machine Learning documentation](https://docs.microsoft.com/en-us/azure/machine-learning/)
- [Azure Pipelines documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/)
- [Azure Machine Learning Python SDK](https://docs.microsoft.com/en-us/python/api/overview/azure/ml/?view=azure-ml-py)
- [Azure Machine Learning CLI](https://docs.microsoft.com/en-us/azure/machine-learning/reference-azure-machine-learning-cli)
