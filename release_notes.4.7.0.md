
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
- #8083 : Admin screen : make the text selectable
- #8184 : Change color of answer in card detail to be coherent with custom screen
- #8159 - Date picker - add new predefined date range
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
  - #7999 : Stop updating screen when user is editing
  - #8109 : Add the possibility to define minWidth for CustomCardList screen
  - #8065 : Add HTML field type
  - #8095 : Add an ack selected button
  - #7921 : Add response field in export
  - #8147 : Filter by state
  - #8013 : Add the possibility to add a select option for user input
  - #8146 : Restricted or authorise one or more lists of entities to respond
  - #8145 : Add alert message when responses are sent
  - #8137 : Add field types STATE_NAME and PROCESS_NAME
  - #8184 : Permit to have more than one line in cells
  - #8129 : Disable buttons if action is not possible
  - #8128 : Enable the ability to configure a column containing acknowledgment icons
  - #8194 : Set a maximum size option for input
  - #8121 : Add the possibility to filter for HTML field in custom card list screen



# Bug Fixes

- #7803 : In archives card display edit button shall never appears in message card example
- #7867 : Fixed long state names in notification configuration
- #7851 cli : "opfab help commands" does not work
- #7799 : Monitoring screen clicking on unlock icon is not updating monitoring result
- #7907 : Do not take emojis into account when sorting AG Grid columns
- #7982 : Process Monitoring Screen: Text column search returns no results
- #8097 : Acknowledgment at the entity level only working with entities with roles sender
- #8117 : Updating a business data with the UI does not work


# Tasks

- #7826 : Avoid security log in cards-publication service on startup
- #7878 : Defined charset to UTF-8 in when saving process monitoring file
- #7989 : Improve "loading in progress" mechanism
- #7896 : Migration to java 21
- #8130 : Correct swagger files for URLs in API documentation

# Dependencies upgrade

## Frontend
- ag-grid 33.2.1
- angular 18.2.17
- bootstrap 5.3.4
- chart.js to v4.4.8
- fullcalendar 6.1.17
- ngx-charts 21.1.3
- virtual-select-plugin 1.0.47


  
## Backend 

### Java services 

- amqp-client 5.25.0
- amqplib 0.10.7
- confluent 7.9.0
- guava v33.4.6-jre
- jre 21.0.6
- json-smart 2.5.2
- kafka-clients 7.9.0-ce 
- micrometer-registry-prometheus 1.14.5
- org.apache.commons:commons-pool2 2.12.1
- slf4j-api 2.0.17
- spring boot 3.4.4
- spring-kafka 3.3.4
- spring security 6.4.4
- spring-webflux 6.2.5

### Node services

- amqplib 0.10.7
- axios 1.8.4
- express 5.1.0
- jsdom 26
- mongodb 6.15.0
- Node 22.14.0
- nodemailer 6.10.0
  

## Misc 

- jackson monorepo 2.18.3
- mongo 7.0.17
- nginx 1.27.4
- rabbitMQ 4.0.8
- actions/upload-artifact 4.6.2





