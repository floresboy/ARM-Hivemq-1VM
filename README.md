# HiveMQ  single Virtual Machine ARM script

This template simply deploys a single Node HiveMQ broker to Azure.


[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffloresboy%2FARM-Hivemq-1VM%2Fmain%2Fazuredeploy.json)


tested : 5 febr 23 > OK

The following resources will be deployed bis this template:
- An Virtual Machine with HiveMQ version of your choise.
- A NSG with port opening for 8080, ssh and 1883/mqtt
- all the HiveMQ enterpise extentions with a 5 hr limit
- 25 MQTT connections max.

see also
https://www.hivemq.com/blog/connect-hivemq-and-azure-event-hubs/
