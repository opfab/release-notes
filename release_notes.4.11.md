
# Features

- #8979 : Display of firstname even if lastname is empty (and vice versa)
- #8987 : Custom screen : add acknowledgment column title for export
- #8695 : Add an attachment option for email sent
- #9155 : For accessiblity, add the possiblity to validate activity area via return key
- #9278 : Add email field to user admin interface
- #9309 : Permit template to provide a destroy method
- #9358 : Usercard : use entity description for searching in multi-select
- #9319 : Move state parameter emailBodyTemplate to email.bodyTemplate
- #9381 : Allow hiding connected users in the activity area screen
- #9277 : Do not set email in the settings
- #9281 : Add an option to hide body prefix and postfix for mail per process/state
- #9283 : Add an option to set a sender for mail per process/state
- #9387 : Opfab cli : add a delete bundle by version method
- #9388 : Process montoring screen : set column width with pixel instead of relative numbers
- #9386 : Process Monitoring screen : export only visible columns
- #9385 : Process monitoring screen : permit user to set column width
- #9383 : Delete user settings when deleted user
  
# Bugs

- #9027 : Solve issue if ack list is too long by adding a vertical scroll bar
- #8909 : Admin screen : id of group exceeds the width of its column sometimes
- #9186 : Do not show tooltip if tooltip content is empty
- #9235 : Missing parent entity prevents card acknowledgment
- #8989 : Custom screen : warnings when displaying custom screen
- #9303 : Realtime screen : popup positioning error

# Tasks

- #9014 : Add new api documentation based on openapi V3
- #9015 : Remove client library
- #9345 : Rename docker names for consistency
- #9382 : Move selectActivityAreaOnLogin web-ui param in activityArea
  
# Dependencies upgrade

## Frontend

- ag-grid 35.0.0
- angular 21.0.6
- chart.js 4.5.1
- fortawesome/fontawesome-free 7.1.0
- fullcalendar 6.1.20
- mongodb 7
- ol(openlayer) 10.7.0
- proj4 2.20.2
- zone.js 0.16.0

## Backend 


### Java services 
- amqp-client 5.28.0
- avro 1.12.1
- commons-io 2.21.0
- commons-lang3 3.20.0
- commons-pool2 2.13.0
- commons-text 1.15.0 
- confluent 8.1.1
- kafka-clients 8.1.1-ce
- jackson 2.20.1
- micrometer-registry-prometheus 1.16.1
- spring boot 3.5.9
- spring-kafka 3.3.11
- spring security 6.5.7
- spring-webflux 7.0.2

  
### Node services

- amqp-connection-manager 5
- axios 1.13.2
- express 5.2.1
- globals 17.0.0
- js-yaml 4.1.1
- nodemailer 7.0.12 
- node.js 24.12.0
- rimraf 6.1.2
- typescript 5.9.3
- winston 3.19.0


## Command Line Interface (CLI)

- node.js 22.21.0
- tar 7.5.2 

## Misc

- rabbitmq 4.2.2

