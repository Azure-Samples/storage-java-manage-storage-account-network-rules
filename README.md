---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Storage
  platforms: java
---

# Getting Started with Storage - Manage Storage Account Network Rules - in Java #


  Azure Storage sample for managing storage account network rules -
  - Create a virtual network and subnet with storage service subnet access enabled
  - Create a storage account with access allowed only from the subnet
  - Create a public IP address
  - Create a virtual machine and associate the public IP address
  - Update the storage account with access also allowed from the public IP address
  - Update the storage account to restrict incoming traffic to HTTPS.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/storage-java-manage-storage-account-network-rules.git

    cd storage-java-manage-storage-account-network-rules

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
