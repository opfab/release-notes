
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
- Custom card list screen
  - #7881 : Add the possibility to define custom card list screens
  - #7917 : Add process and type of state filters for custom card list screen
  - #7922 : Custom card list screen : add response from my entities column
  - #7923 : Custom card list screen : add response from my entities filter
  - #7920 : In custom card list screen, add colored circle field type
  - #7947 : Custom card list screen : add option to show a response button
  - #7880 : Add the possibility to access custom opfab screen in menu
  - #7870 : Add custom data field to light cards
  - #7976 : Custom card list screen : add the possibility to put user input in responses
  - #7925 Custom card list screen : add lines per page choice for result table


# Bug Fixes

- #7803 In archives card display edit button shall never appears in message card example
- #7867 Fixed long state names in notification configuration
- #7851 cli : "opfab help commands" does not work
- #7799 : Monitoring screen clicking on unlock icon is not updating monitoring result
- #7907 : Do not take emojis into account when sorting AG Grid columns
- #7982 : Process Monitoring Screen: Text column search returns no results


# Tasks

- #7826 : Avoid security log in cards-publication service on startup
- #7878 : Defined charset to UTF-8 in when saving process monitoring file
- #7989 : Improve "loading in progress" mechanism

# Dependencies upgrade

## Frontend
- ag-grid 33.0.4
- angular  18.2.14
- ngx-charts 21.1.3
- virtual-select-plugin 1.0.47


  
## Backend 

### Java services 

- amqp-client 5.25.0
- confluent 7.8.1
- json-smart 2.5.2
- kafka-clients 7.8.1-ce 
- micrometer-registry-prometheus 1.14.4
- org.apache.commons:commons-pool2 2.12.1
- spring boot 3.4.2
- spring-kafka 3.3.3 
- spring-webflux 6.2.3

### Node services

- jsdom 26
- mongodb 6.13.0 
- Node 22.13.1
- nodemailer 6.10.0
  

## Misc 

- nginx 1.27.4
- rabbitMQ 4.0.6





