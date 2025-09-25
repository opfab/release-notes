
# Features

- #8698 : Cli : Add an error message when trying to remove unexisting supervised entity
- #8678 : Process Monitoring Screen : add a panel to filter column list
- #8797 : Geomap : Add an option to include credentials for WMTS layer
- #8620 : Improve timeline navigation for past data
- #8810 : Remove active date range picker in Logging screen
- #8821 : Make unchecked by default checkbox 'cards with response from my entities' for a custom screen
- #8707 : Implement set filter in process monitoring
- #8811 : Change label to 'Send email on card reception' on settings screen
- #8713 : User actions log : replace the two date pickers with a date range picker
- #8932 : Using JSON5 instead of JSON format for CLI (permit to have comments in json files)
- #8923 : Dates in e-mail recaps - Reception date instead of period


# Bugs

- #8828 : Impossible to filter on more than one column on process monitoring screen
- #8712 : Built in template task : should not be possibe to set empty time
- #8902 : Wrong display on activity area screen when user is member of an entity having two parents with one not an activity area group


# Tasks

- #8002 : Remove deprecated way of responding to opfab.currentCard.registerFunctionToGetUserResponse
- #8899 : Remove default rabbit password from services

  
# Dependencies upgrade

## Frontend

- ag-grid 34.2.0
- angular 20.3.2
- bootstrap 5.3.8
- fortawesome/fontawesome-free 7.0.1
- fullcalendar 6.1.19
- jasmine 5.1.9
- ng-bootstrap 19.0.1
- nginx docker 1.29.1
- ngx-translate 17.0.0
- node 22.18.0
- typescript 5.9.2
- virtual-select-plugin 1.1.0

## Backend 


### Java services 



- commons-compress 1.28.0
- commons-io 2.20.0
- commons-lang3 3.19.0
- commons-text 1.14.0
- guava 33.5.0-jre
- handlebars 4.5.0
- jackson 2.20.0
- json-smart 2.6.0
- micrometer-registry-prometheus 1.15.4
- rabbitMQ 5.26.0
- spring boot 3.5.6
- spring-kafka 3.3.10
- spring security 6.5.5
- spring-webflux 6.2.11


  
### Node services

- amqplib 0.10.9
- axios 1.12.2
- config 4.1.1
- globals 16.4.0
- jsdom 27.0.0
- mongodb 6.20.0
- nodemailer 7.0.6
- node.js 22.19.0
- typescript 5.9.2
- types/node 22.18.6

## Command Line Interface (CLI)

- tar: 7.4.4


## Misc

- mongo 7.0.24
- rabbitmq Docker v4.1.4 




