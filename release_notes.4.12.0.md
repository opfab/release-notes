
# Features

- #9565 : Notification configuration: add thicker red line to the “mail not activated” icon
- #9564 : Monitoring processus screen : set entity names in entity recipients columns
- #9566 : In all adminstration screens do not close popups with esc key
- #9662 : Opfab CLI : offer more options for command "user last-user-action"
- #9661 : Add creation date in admin user screen
- #9609 : Allow asynchronous processing in templates before sending response or usercard
- #9610 : Add a possibility for template to get response from child card sending
- #8693 : Add the possiblity to pop mailboxes and convert mail to cards
  
# Bugs

- #9615 : Multiple stop and start of supervisor trigger too much check


# Tasks

- #9581 : Rename cards-external-diffusion to email-gateway
- #9590 : Move configuration parameters operatorfabric.mail* to operatorfabric.emailGateway.smtpServer
- #9592 : Move configuration parameters operatorfabric.emailGateway.defaultConfig.* to operatorfabric.emailGateway.defaultConfig.outgoingEmails  

  
# Dependencies upgrade

## Frontend

- ag-grid 35.1.0
- angular 21.2.1
- fortawesome/fontawesome-free 7.2.0
- ol(openlayer) 10.8.0
- proj4 2.20.4
- zone.js 0.16.1

## Backend 


### Java services 

- amqp-client 5.29.0
- java 21.0.10
- kafka-clients 8.2.0-ce
- micrometer-registry-prometheus 1.16.4 
- spring boot 4.0.3
- spring security 7.0.3
  
### Node services

- axios 1.13.6
- config 4.4.1
- globals 17.4.0
- jwks-rsa 4.0.1
- mongodb 7.1.0
- nodemailer 8.0.2
- node.js 24.14.0
- rimraf 6.1.3
- yaml 2.8.2


## Command Line Interface (CLI)

- node.js 24.14.0
- tar 7.5.11
  
## Misc

- RabbitMQ 4.2.4-management
