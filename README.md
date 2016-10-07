---
services: networking
platforms: java
author: anuchandy
---

# Getting Started with Networking in Java: Manage IP Address

This sample shows how to use Java to manage an IP address for your Microsoft Azure network.

The sample performs these tasks:

   - Assign a public IP address for a virtual machine during its creation
   - Assign a public IP address for a virtual machine through an virtual machine update action
   - Get the associated public IP address for a virtual machine
   - Get the assigned public IP address for a virtual machine
   - Remove a public IP address from a virtual machine. 

## Run this sample

To run this sample:

1. If you don't already have a Microsoft Azure subscription, you can register for a [free trial account](http://go.microsoft.com/fwlink/?LinkId=330212).

2. Install the [Azure Management Libraries for Java](https://github.com/Azure/azure-sdk-for-java/). These libraries contain the Azure Storage Resource Provider.

3. Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md) for more information.

4. Clone this repository: 

	    git clone https://github.com/Azure-Samples/network-java-manage-ip-address.git

5. Navigate to the source directory for the sample:

	    cd network-java-manage-ip-address

6. Build the project with [Maven](https://maven.apache.org/download.cgi):

	    mvn clean compile exec:java


## More information ##

- [Microsoft Azure Java developer center](https://azure.microsoft.com/en-us/develop/java/)
- [Public IP Address - Overview](https://azure.microsoft.com/documentation/articles/virtual-network-ip-addresses-overview-arm/)
- [Virtual Networks - Overview](https://azure.microsoft.com/documentation/articles/virtual-networks-overview/)
- [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/)
- [Virtual Machines - Learning Path](https://azure.microsoft.com/documentation/learning-paths/virtual-machines/)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
