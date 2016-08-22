# SQL Azure Monitoring

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-sqlazure-oms-monitoring%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-sqlazure-oms-monitoring%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

Operations Management Suite (OMS) is a management offering which provides monitoring for Azure Resources through the Log Analytics service. Log Analytics enables users to collect, correlate and visualize structured and unstructured data. Through the out of the box solutions available in OMS Log Analytics, users can easily monitor and receive notifications on the health of their Azure Resources such as SQL Azure. Microsoft Azure SQL Database, also known as SQL Azure, is a scalable relational database service that provides familiar SQL-Server-like capabilities to applications running in Azure cloud. OMS Log Analytics collects and visualizes the important SQL Azure performance metrics and enables users to easily create custom monitoring rules in addition to those provided with the solution. OMS Log Analytics enables you to monitor across multiple Azure subscriptions, resources and elastic pools and more importantly lets you identify issues at each layer of your application stack. 

This solution (currently in private preview) will allow you to capture your Azure SQL database metrics (across subscriptions and elastic pools) and visualize them in Operations Management Suite (Log Analytics). This solution currently leverages an automation runbook in Azure Automation, the Log Analytics Ingestion API, together with Log Analytics to present data about all your SQL databses in a single log analytics workspace. 

![alt text](images/SQLAzurePaaS.png "SQL Azure Monitoring")

