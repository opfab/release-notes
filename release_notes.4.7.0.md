
# Features

- #7787 : Add vertical scrolling inside array in admin screens
- #7592 : Add an API frontend method to send response card
- #7706 : Add the possibility to send card on behalf of user instead of entity
- #7847 : Add first name and last name on real time screen instead of login
- #7850 : Add possibility to hide publisher multiselect in usercard
- #7876 : Add first name and last name of user on activity area screen
- #7877 : Add an option to not received card details
- #7708 : Add support for loading custom global CSS
- #7883 : Add an option to notify the user only when the card is reminded
- #7786 : In activity area, permit to select/unselect a group of activity area in one click
- #7952 : Simplify interface for getting user response from template
- #7852 : Add the possibility to add comments in opfab cli commands file
- #7902 : Add the possibility to call a custom method before sending usercard
- #7784 : Add selection of number of lines per page in user action logs
- #7875 : Always set child card startDate to parent startDate
- #8004 : In some screens, switching pagination row number sometimes does not refresh correctly the tables
- #7961 : Add possibility in ui templates to set severity for child cards when responding to card
- #7997 : Do not erase entity/group membership when updating an entity/group via API
- Custom card list screen
  - #7881 : Add the possibility to define custom card list screens
  - #7917 : Add process and type of state filters for custom card list screen
  - #7922 : Add response from my entities column
  - #7923 : Add response from my entities filter
  - #7920 : Add colored circle field type
  - #7947 : Add option to show a response button
  - #7880 : Add the possibility to access custom opfab screen in menu
  - #7870 : Add custom data field to light cards
  - #7976 : Add the possibility to put user input in responses
  - #7925 : Add lines per page choice for result table
  - #7981 : Add the possiblity to integrate user responses in the result array
  - #8021 : Dashboard : permit to redirect to a custom screen
  - #7967 : Add a header filter ack an read
  - #7904 : Add loading spinner in custom card list screen
  - #8066 : Adjust response button size to content
  - #7998 : Show response buttons and checkboxes only when all cards have been loaded
  - #8009 : Use processIds to restrict the process list
  - #8064 : Use getValue if exist in customscreen configuration


# Bug Fixes

- #7803 In archives card display edit button shall never appears in message card example
- #7867 Fixed long state names in notification configuration
- #7851 cli : "opfab help commands" does not work
- #7799 : Monitoring screen clicking on unlock icon is not updating monitoring result
- #7907 : Do not take emojis into account when sorting AG Grid columns
- #7982 : Process Monitoring Screen: Text column search returns no results
- #8097: Acknowledgment at the entity level only working with entities with roles sender


# Tasks

- #7826 : Avoid security log in cards-publication service on startup
- #7878 : Defined charset to UTF-8 in when saving process monitoring file
- #7989 : Improve "loading in progress" mechanism
- #7896 : Migration to java 21

# Dependencies upgrade

## Frontend
- ag-grid 33.1.1
- angular  18.2.14
- chart.js to v4.4.8
- ngx-charts 21.1.3
- virtual-select-plugin 1.0.47


  
## Backend 

### Java services 

- amqp-client 5.25.0
- amqplib 0.10.7
- confluent 7.9.0
- jre 21.0.6
- json-smart 2.5.2
- kafka-clients 7.9.0-ce 
- micrometer-registry-prometheus 1.14.4
- org.apache.commons:commons-pool2 2.12.1
- slf4j-api 2.0.17
- spring boot 3.4.3
- spring-kafka 3.3.3
- spring security 6.4.3
- spring-webflux 6.2.3

### Node services

- axios 1.8.2
- jsdom 26
- mongodb 6.14.2
- Node 22.14.0
- nodemailer 6.10.0
  

## Misc 

- jackson monorepo 2.18.3
- mongo 7.0.17
- nginx 1.27.4
- rabbitMQ 4.0.7





