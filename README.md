---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Network
  platforms: java
---

# Getting Started with Network - Manage IP Address - in Java #


  Azure Network sample for managing IP address -
  - Assign a public IP address for a virtual machine during its creation
  - Assign a public IP address for a virtual machine through an virtual machine update action
  - Get the associated public IP address for a virtual machine
  - Get the assigned public IP address for a virtual machine
  - Remove a public IP address from a virtual machine.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-ip-address.git

    cd network-java-manage-ip-address

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.