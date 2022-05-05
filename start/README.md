# Initial Azure deployment 

Please specify resources location and create a new resource group.
This temlate will create
* Resource Group
* API Connection. Connection between Event Grid Topic and Logic app.
* Event Grid Topic.
* Logic app with subscribtion on **queues.conversations.emails** with initial steps. 
* Managed Identity. Secure access between Logic app and API Connection.

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FNoralogix%2Fgenesyscloud-eventgrid%2Fmain%2Fstart%2Fgc-eventgrid-repo361.json)

[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FNoralogix%2Fgenesyscloud-eventgrid%2Fmain%2Fstart%2Fgc-eventgrid-repo361.json)

After deployment go to Outputs and copy EventGrid Endpoint, EventGrid Secret to https://eventgrid.repo361.com/
![lab image](images/start-deployment-eventgrid-outputs.png)

List of [samples](https://github.com/Noralogix/genesyscloud-eventgrid/tree/main/samples)
