---
services: virtual-network
platforms: java
author: anuchandy
---

#Getting Started with Network - Manage IP Address - in Java #


Network: Manage IP Address Sample (for 1.0.0-beta2) - demonstrates how to perform common tasks using the Microsoft Azure Network service.

   - Assign a public IP address for a virtual machine during its creation
   - Assign a public IP address for a virtual machine through an virtual machine update action
   - Get the associated public IP address for a virtual machine
   - Get the assigned public IP address for a virtual machine
   - Remove a public IP address from a virtual machine.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-ip-address.git

    cd network-java-manage-ip-address

    mvn clean compile exec:java

## More information ##

[http://azure.com/java] (http://azure.com/java)

[Public IP Address - Overview](https://azure.microsoft.com/en-us/documentation/articles/virtual-network-ip-addresses-overview-arm/)

[Virtual Networks - Overview](https://azure.microsoft.com/en-us/documentation/articles/virtual-networks-overview/)

[Virtual Machines](https://azure.microsoft.com/en-us/services/virtual-machines/)

[Virtual Machines - Learning Path](https://azure.microsoft.com/en-us/documentation/learning-paths/virtual-machines/)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
