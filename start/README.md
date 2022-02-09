# Initial Azure deployment 

You can specify project name.
This temlate will create 
* Resource Group
* Event Grid
* Logic App with subscribtion on **conversation.email**

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FNoralogix%2Fgenesyscloud-eventgrid%2Fmain%2Fstart%2Fgc-eventgrid-repo361.json)

[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FNoralogix%2Fgenesyscloud-eventgrid%2Fmain%2Fstart%2Fgc-eventgrid-repo361.json)

After deployment go to output section and copy EventGrid Endpoint, EventGrid Secret to https://eventgrid.repo361.com/

List of [samples](https://github.com/Noralogix/genesyscloud-eventgrid/samples/)