# styra-kafka-custom-system

# How to create a System In Das 

   Steps for Creating System 
   
1. Install and Configure the Styra CLI 

To create and install new system-types in your DAS tenant, you will need to install and configure the Styra CLI. Skip this step if you have already installed and configured the Styra CLI. 
From your target tenant, create an API token and store it somewhere secure (1Password or simply a text file on your local disk): 

From your command line run :

macOS 
$ curl -L -o styra https://docs.styra.com/v1/docs/bin/darwin/amd64/styra && chmod 755 styra



Linux 
$ curl -L -o styra https://docs.styra.com/v1/docs/bin/linux/amd64/styra && chmod 755 styra



Move the Styra CLI into your executable path:
$ mv styra /usr/local/bin/styra




