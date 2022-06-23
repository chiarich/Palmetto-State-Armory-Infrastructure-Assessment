# Palmetto-State-Armory-Infrastructure-Assessment
This template creates the aws 2 tier architecture.
We have provided all the required properties values in template before you provision it.
Few of the properties are hardcoded due to time constraints like vpc id image id and subnet id.
Template can be improved for dynamic execution and few of the things like parameters and outputs section can be introduced in it.
Template integrates the resources created in template as per the requirement.

As a user you just need to upload this cloudformation template in your aws account and change value of Certain variables like image id and subnet id and automatically the stack will create all required infrastructure in aws account.

Below is the screenshot for the load balancer DNS address.

We can create tunnel with web servers with open source software like navicat or others which provide sql functionality and then telnet towards db endpoints. Since it is going to take some time to setup, so this can be added as an improvement.

Also we can tail access logs of webservers by SSH-ing into the webserver instances and see which instance the request is coming into when we hit the load balancer DNS address URL from browser
