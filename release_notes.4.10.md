
# Features

- #8698 : Cli : Add an error message when trying to remove unexisting supervised entity
- #8678 : Process Monitoring Screen : add a panel to filter column list
- #8797 : Geomap : Add an option to include credentials for WMTS layer
- #8620 : Improve timeline navigation for past data


# Bugs

- #8828 : Impossible to filter on more than one column on process monitoring screen


# Tasks

- #8002 : Remove deprecated way of responding to opfab.currentCard.registerFunctionToGetUserResponse

  
# Dependencies upgrade

## Frontend
- fullcalendar v6.1.19
- nginx docker v1.29.1
- node 22.18.0
- virtual-select-plugin 1.1.0

## Backend 


### Java services 

- commons-io 2.20.0
- handlebars 4.5.0
- json-smart 2.6.0
- micrometer-registry-prometheus 1.15.3
- rabbitMQ 5.26.0
- spring boot 3.5.5 
- spring-kafka 3.3.9
- spring security 6.5.3 
- spring-webflux 6.2.10


  
### Node services

- amqplib 0.10.9 
- config 4.1.1
- mongodb 6.19.0 
- types/node 22.17.2

## Misc

- apache.commons-compress 1.28.0
- apache.commons-text 1.14.0
- mongo 7.0.23
- rabbitmq Docker v4.1.4 
- swagger-ui 5.27.1




