
# Features

- #9565 : Notification configuration: add thicker red line to the “mail not activated” icon
- #9564 : Monitoring processus screen : set entity names in entity recipients columns
  
# Bugs


# Tasks

- #9581 : Rename cards-external-diffusion to email-gateway
- #9590 : Move configuration parameters operatorfabric.mail* to operatorfabric.emailGateway.smtpServer
- #9592 : Move configuration parameters operatorfabric.emailGateway.defaultConfig.* to operatorfabric.emailGateway.defaultConfig.outgoingEmails  

  
# Dependencies upgrade

## Frontend

- ag-grid 35.1.0
- angular 21.1.5
- fortawesome/fontawesome-free 7.2.0
- ol(openlayer) 10.8.0
- zone.js 0.16.1

## Backend 


### Java services 

- java 21.0.10
- micrometer-registry-prometheus 1.16.3 
- spring boot 4.0.2
- spring security 7.0.3
  
### Node services

- axios 1.13.5
- config 4.3.0
- mongodb 7.1.0
- nodemailer 8
- node.js 24.13.1
- rimraf 6.1.3


## Command Line Interface (CLI)

- tar 7.5.9
  
## Misc

