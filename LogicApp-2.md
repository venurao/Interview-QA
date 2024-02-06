# Q: What is Azure Logic Apps?
Ans:
Azure Logic Apps is a fully managed integration Platform as a Service (PaaS), that is a cloud-based platform for
developing and deploying automated processes that integrate your apps, data, services, and systems.
Q: What is the difference between Azure functions and logic apps?
Ans:
Azure Functions is a serverless compute service, and Azure Logic Apps is a serverless workflow service. 
Both can build complicated orchestrations. An orchestration is a set of functions or tasks, 
known as actions in Logic Apps, which are performed in order to complete a difficult task.
Q: What are connectors in Azure Logic Apps?
Ans:
Connectors are used in Azure Logic Apps to accomplish certain actions or processes. 
These connectors are intended to connect to and interact with user data. For Azure Logic Apps,
there are several connectors available, including Enterprise connectors. Users have the option of using pre-defined 
connectors or creating their own unique connectors. Connectors can also be defined using ARM templates.
Connectors in Azure Logic Apps can function as either actions or triggers.
Q: What are Actions in Azure Logic Apps?
Ans:
Actions are the steps that are performed once the trigger is activated. When an Azure Logic App is started, 
a series of actions are performed to complete the workflow. Actions are processes that will carry out the 
specified business task based on the data supplied by the user. Users can choose the required action from 
the connector repository's collection of actions.
Take a look at our suggested post :
Azure Active Directory Interview Questions
Azure Cosmos DB Interview Questions
Azure Data Factory Interview Questions
Azure DevOps Interview Questions
Azure Fabric Interview Questions
Azure Functions Interview Questions
Jenkins Interview Questions
SonarQube Interview Questions
Q: How would you add connectors to Azure Logic Apps?
Ans:
1.	Navigate to the Azure portal and select Create a resource.
2.	In the search box, type Logic Apps Custom Connector and choose it from the drop-down menu.
3.	Select Create in Logic Apps Custom Connector.
4.	Register the connector by entering the details and selecting Review + Create.
5.	After reviewing the information, click Create.
6.	The menu appears automatically once users create the custom connector resource. If it doesn't, 
you can go directly to the subscription and resource group you chose and open it. 
Users can define the connector's behavior using the custom connector.
Q: How many custom connector can be created in an Azure subscription?
Ans:
We can create up to 1,000 custom connectors per Azure subscription.
Q: Is it possible to have multiple triggers in an Azure Logic App?
Ans:
Yes, Azure Logic App can have multiple triggers configured. A Logic App workflow can accept multiple triggers.
Q: How many different types of triggers are there in Azure Logic Apps?
Ans:
There are two main types of triggers:
1.	Built-in triggers
Built-in triggers are predefined triggers that activate Azure Logic Apps according to a schedule and the HTTP protocol.
Many built-in trigger types are available, including HTTP, HTTPWebhook, Recurrence, and Request.
2.	Managed API triggers
Managed API triggers are built on API connections and API Webhook connections that use custom connectors to check 
an endpoint.
Q: Which type of trigger has to be used to start the azure logic app?
Ans:
An Azure alert notification can be routed to other systems via webhooks for specific processing or actions. 
A webhook on an alert can be used for a variety of purposes, including routing it to SMS messaging services, 
bug logging, alerting a team using messaging or chat services, and more.
Q: How to update the state of a workflow step in an Azure Logic App
Ans:
To do this, actions of the webhook type should be used. A webhook action will send out a subscribe request once it has 
begun running and will provide a specific callback URI that can be used to resume the action. 
To keep the state up to date and give the logic app instructions about when to resume, 
we would require external service (using invoke the callback URI).

