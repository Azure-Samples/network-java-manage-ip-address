---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: virtual-network
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

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-ip-address.git

    cd network-java-manage-ip-address

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.