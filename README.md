---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Kubernetescluster
  platforms: java
---

# Getting Started with Kubernetescluster - Manage Kubernetes Cluster With Customer Managed Key - in Java #


  Azure Container Service (AKS) sample for managing a Kubernetes cluster with customer-managed key.
    - Create a key vault with purge-protection enabled
    - Create a key in key vault
    - Create a disk encryption set using the created key as the encryption key with automatic key-rotation
    - Grant the des access to the key vault
    - Create an Azure Container Service (AKS) with managed Kubernetes cluster, os disk encrypted using customer-managed key
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/aks-java-manage-encrypted-kubernetes-cluster-with-customer-managed-key.git

    cd aks-java-manage-encrypted-kubernetes-cluster-with-customer-managed-key

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
