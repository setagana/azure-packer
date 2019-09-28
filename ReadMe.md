# azure-packer

This container is based on Debian stretch and contain the [Azure CLI](https://github.com/Azure/azure-cli) and [Packer](https://www.packer.io).

The container is intended for use in [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) container jobs to create images on Azure.

Folders represent the tags of the image, and mirror the Packer version which is installed.