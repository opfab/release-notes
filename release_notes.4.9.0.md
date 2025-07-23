
# Features

- #8245 : Custom screen - buttons shall be grey as soon as response has been send
- #8479 : Add style for dropdown menus when selected
- #8482 : Custom screens - make sorting by severity possible
- #8503 : Add an option to update first name and last name from token
- #8331 : Store last user connection in database
- #8599 : Improve escapeHtml method and security documentation
- #8262 : Add entity emitter and recipients in archives filters
- #8477 : keep header table visible when scrolling for admin and logging screens
- #7951 : Custom screens: change table checkbox style to opfab style
- #8574 : Set font-size to 24 for question template
- #8603 : Numerical filtering/sorting in custom screens
- #8646 : Add a UI API method to retrieve child cards for current user
- #8657 : Remove summary and business date from mail title and mail body
- #8659 : Geomap : add WMTS support and refacto configuration format

# Bug

- #8239 : Custom screens - Sorting takes into account emoticones whereas it should not
- #8472 : Feed : Process multifilter list not visible
- #8606 : Export in Excel of a select type value from a custom screen
- #8625 : Menu with custom screens links does not disappear
- #8637 : Realtime screen - with option onlyDisplayUsersInGroups users with firstname and lastname are not visible
- #8394 : Set consistant font-size between preview and card detail

# Tasks

- #8262 : Simplify opfab start and configuration
- #8545 : Remove ngx-chips library
- #8478 : Incorrect URL in Card Management API doc
- #8564 : Remove ngx-charts library
  
# Dependencies upgrade

## Frontend

- ag-grid 34.0.2
- angular 19.2.15
- chart.js v4.5.0
- fullcalendar v6.1.18
- ol(openlayer) 10.6.1
  
## Backend 


### Java services 

- commons-lang3 3.18.0
- confluent 8.0.0
- jackson 2.19.1
- kafka-clients 8.0.0-ce
- micrometer-registry-prometheus 1.15.2
- spring boot v3.5.3
- spring-kafka 3.3.7
- spring security 6.5.1
- spring-webflux 6.2.9
  
### Node services
 - axios 1.10.0
 - config 4.0.1
 - mongodb 6.17.0
 - node 22.17.0
 - nodemailer 7.0.5
 - typescript 5.8.3

## Misc

- nginx Docker 1.29.0
- rabbitmq 4.1.2






