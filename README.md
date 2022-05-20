# Genesys Cloud Notifications
Genesys Cloud has many real time data notifications that can be used, these can be found at [available topics](https://developer.Genesys.cloud/api/rest/v2/notifications/available_topics)
The list is extensive and is regularly being updated. For the best performance we recommend the following: 
* The client share with Noralogix their business modelling around real time notification data, we can then recommend the best real time Genesys Cloud notifications to use for their business model,  
* Noralogix can also assist the client with the following modelling and designing on their internal Microsoft Azure instance, Microsoft Azure Event Grid and Microsoft Azure Event Handles.

# So, what is Microsoft Event Grid?
Microsoft Azure Event Grid allows you to easily build applications with event-based architectures. 
First, select the Genesys Cloud notification you would like to subscribe to, and then give the event handler or Webhook endpoint to send the event to. You can use filters to route specific events to different endpoints, multicast to multiple endpoints, and make sure your events are reliably delivered. Microsoft Azure Event Grid is deployed to maximize availability by natively spreading across multiple fault domains in every region, and across availability zones (in regions that support them).

# Microsoft Azure concepts  
There are five concepts in Azure Event Grid that let you get going: 
* Events - Genesys Cloud Notifications  
* Event sources - Noralogix EventGrid
* Topics - The endpoint where publishers send events. 
* Event subscriptions - The endpoint or built-in mechanism to route events, sometimes to more than one handler. Subscriptions are also used by handlers to intelligently filter incoming events. 
* Event handlers - Azure Logic Apps or Azure Function reacting to the event.

# What can a client do with Event Grid?
Event Grid connects Genesys Cloud notifications and event handlers in Azure.

# Noralogix Event Grid topics
#### For Queues
- [analytics.queues.observations](https://github.com/Noralogix/genesyscloud-eventgrid/tree/main/samples/queues-analytics-observations)
- queues.conversations.emails
- queues.conversations
- queues.conversations.chats
- queues.conversations.calls
- queues.conversations.callbacks
- users.conversations.calls
- queues.users

#### For Agents
- analytics.users.aggregates
- analytics.users.aggregates
- users.presence
- users.activity
- users.routingStatus


Initial Azure [deployment](https://github.com/Noralogix/genesyscloud-eventgrid/tree/main/start) 

For more information please contact: [contactus@noralogix.com](mailto:contactus@noralogix.com)
