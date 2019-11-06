# EmailService

Reactive service responsible for email communication with customers.
Service listens to events emitted by other services and based on them
decides which email should be sent out to customers.   

Owner|Tier|Status|Landscape|Contexts
---|---|---|---|---
CommunicationsTeam|Tier2|Prod|Web|Customers,Orders,Catalog

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

