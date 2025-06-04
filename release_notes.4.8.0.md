
# Features

- #8244 : Make text selectable in logging screen and in external device configuration
- #8248 : Horizontal scrolling in cards for wide content
- #8247 : Usercard Payload Size Limitation - Error Handling
- #8361 : Authorize special characters in processInstanceId (except the slash)
- #8349 : Optional confirmation popup when responding to a card
- #8261 : Add date range picker in monitoring process screen
- #8416 : Opfab input mono-select with free text possibility in Custom screen
- #8418 : Custom card list : add the option to set response possible only for specific process states
- #8392 : Permit to use the e-mail address from the Jwt Token
- #8417 : Custom screen - Pre-selected value for type of state multiselect
- #8439 : Custom screen : sorting and filtering of answers column
- #8420 : Make possible to not include the card link in the e-mail notifications
- #8419 : Make configurable the possibility to force the e-mail format
- #8440 : Custom card list screen : add an option to show only cards emitted by current user entities
- #8421 : Remove the setting related to the "card content in emails" (#8421)

# Bug

- #8131 : Impossible to load font for external app example
- #8268 : Conference template example does not work
- #8438 : Custom screen - response text in last column is cut
- #8462 : Custom screen menu shall be bold and underline if selected


# Tasks

- #8191 : Fix links to files in the documentation
  
# Dependencies upgrade

## Frontend

- ag-grid 33.3.1
- angular 19.2.14
- bootstrap 5.3.6
- chart.js 4.4.9
- ng-bootstrap 18.0.0
- ngx-charts 22.0.0
- typescript 5.8.3
  
## Backend 

### Java services 

- amqplib 0.10.8
- commons-collections4 v4.5.0
- commons-io 2.19.0
- commons-text 1.13.1
- confluent 7.9.1
- guava 33.4.8-jre
- jackson v2.19.0
- jre 21.0.7
- micrometer-registry-prometheus 1.15.0
- spring boot 3.5.0
- spring-kafka 3.3.6
- spring-security 6.5.0
- spring-webflux 6.2.7

### Node services

- axios 1.9.0
- config v4.0.0
- globals 16.1.0
- jsdom 26.1.0
- mongodb 6.16.0
- node 22.15.1
- nodemailer 7.0.3


## Misc

- kafka-clients 7.9.1-ce
- mongo 7.0.20
- nginx 1.28.0
- rabbitMQ 4.1.0







