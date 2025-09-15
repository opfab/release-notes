
# Features

- #8698 : Cli : Add an error message when trying to remove unexisting supervised entity
- #8678 : Process Monitoring Screen : add a panel to filter column list
- #8797 : Geomap : Add an option to include credentials for WMTS layer
- #8620 : Improve timeline navigation for past data
- #8810 : Remove active date range picker in Logging screen
- #8821 : Make unchecked by default checkbox 'cards with response from my entities' for a custom screen
- #8707 : Implement set filter in process monitoring
- #8811 : Change label to 'Send email on card reception' on settings screen


# Bugs

- #8828 : Impossible to filter on more than one column on process monitoring screen
- #8712 : Built in template task : should not be possibe to set empty time


# Tasks

- #8002 : Remove deprecated way of responding to opfab.currentCard.registerFunctionToGetUserResponse

  
# Dependencies upgrade

## Frontend
- angular 20.2.4
- bootstrap 5.3.8
- fullcalendar 6.1.19
- jasmine 5.1.9
- ng-bootstrap 19.0.1
- nginx docker 1.29.1
- ngx-translate 17.0.0
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
- node.js 22.19.0
- types/node 22.17.2

## Misc

- apache.commons-compress 1.28.0
- apache.commons-text 1.14.0
- mongo 7.0.24
- rabbitmq Docker v4.1.4 
- swagger-ui 5.28.1




