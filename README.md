# EmailService

Reactive service responsible for email communication with customers.
Service listens to events emitted by other services and based on them
decides which email should be sent out to customers.   

Owner|Tier|Status|SLA|Contexts
---|---|---|---|---
CommunicationsTeam|Tier2|Prod|90%|Web,Customers,Orders,Catalog

##### Environments

Production:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://...

Staging:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://... 

##### Tech

- Java: implementation
- AWS ECS: execution env 
- AWS SWF: workflow engine

##### Alerts

- [P1] Amount of errors in DLQ > 100
- [P2] Amount of errors in DLQ > 1
- [P2] Amount of messages in input queue > 500
- [P5] Warnings in the logs

##### Metrics

- [Amount of sent emails](https://...)
- [Amount of hardbounced emails](https://...)
- [Amount of failed email deliveries](https://...)
