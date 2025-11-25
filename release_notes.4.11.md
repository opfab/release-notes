
# Features

- #8979 : Display of firstname even if lastname is empty (and vice versa)
- #8987 : Custom screen : add acknowledgment column title for export
- #8695 : Add an attachment option for email sent
- #9155 : For accessiblity, add the possiblity to validate activity area via return key

# Bugs

- #9027 Solve issue if ack list is too long by adding a vertical scroll bar
- #8909 : Admin screen : id of group exceeds the width of its column sometimes
- #9186 : Do not show tooltip if tooltip content is empty
- #9235 : Missing parent entity prevents card acknowledgment
- #8989 : Custom screen : warnings when displaying custom screen

# Tasks

- #9014 : Add new api documentation based on openapi V3
- #9015 : Remove client library


  
# Dependencies upgrade

## Frontend

- ag-grid 34.3.1
- angular 20.3.13
- chart.js 4.5.1
- fortawesome/fontawesome-free 7.1.0
- mongodb 7
- ol(openlayer) 10.7.0
- proj4 2.20.2

## Backend 


### Java services 
- amqp-client 5.27.1
- avro 1.12.1
- commons-io 2.21.0
- commons-lang3 3.20.0
- confluent 8.1.0
- jackson 2.20.1
- micrometer-registry-prometheus 1.16.0
- spring boot to 3.5.8
- spring-kafka 3.3.11
- spring security 6.5.7
- spring-webflux 7.0.0

  
### Node services

- amqp-connection-manager 5
- axios 1.13.2
- js-yaml 4.1.1
- nodemailer 7.0.10 
- node.js 24.11.1
- rimraf 6.1.2
- typescript 5.9.3
- winston 3.18.3


## Command Line Interface (CLI)

- node.js 22.21.0
- tar 7.5.2 

## Misc

- rabbitmq v4.2.0 

