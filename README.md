# llSPS-INT-479-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding

Intelligent Customer Help Desk with Smart Documement Understanding.
The project is built with the help of Watson Assistant, Discovery, Cloud Function and Node Red app of IBM Cloud. 

#Project Description : The ordinary customer help chatbot answers simple questions, such as store directions,hours and locations. But if the customer asks a question which is totally unrelated to the set of questions given it gives an output as I didn’t understand or you’ve the option to speak to the representative

In this project, we are using Smart Document Understanding So if the customer has any query about the device and its working the application shall pass the question onto Watson Discovery Service. This is pre-loaded with the device’s owners manual. To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries. Scope of Work Create a customer care dialog skill in Watson Assistant Use Smart Document Understanding to build an enhanced Watson Discovery collection Create an IBM Cloud Functions web action that allows Watson Assistant to post queries to Watson Discovery Build a web application with integration to all these services & deploy the same on IBM Cloud Platform

In Watson Discovery I have added ecobee3_userguide.

Node-Red Dashboard link after deploying : https://node-red-ubobq.eu-gb.mybluemix.net/ui/

Youtube video link is : https://youtu.be/A4M6yowisVg

You can find the discovery manual, cloud function code, node-red flow and assistant skill file above.
