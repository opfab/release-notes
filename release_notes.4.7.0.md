
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
- Custom card list screen
  - #7881 : Add the possibility to define custom card list screens
  - #7917 : Add process and type of state filters for custom card list screen
  - #7922 : Custom card list screen : add response from my entities column
  - #7923 : Custom card list screen : add response from my entities filter
  - #7920 : In custom card list screen, add colored circle field type
  - #7947 : Custom card list screen : add option to show a response button
  - #7880 : Add the possibility to access custom opfab screen in menu


# Bug Fixes

- #7803 In archives card display edit button shall never appears in message card example
- #7867 Fixed long state names in notification configuration
- #7851 cli : "opfab help commands" does not work



# Tasks

- #7826 : Avoid security log in cards-publication service on startup
- #7878 : Defined charset to UTF-8 in when saving process monitoring file

# Dependencies upgrade

## Frontend
- ag-grid v33.0.4
- angular  v18.2.14 
- virtual-select-plugin v1.0.47
- ngx-charts v21.1.3

  
## Backend 

### Java services 

- amqp-client v5.25.0
- micrometer-registry-prometheus 1.14.4
- org.apache.commons:commons-pool2 2.12.1
- spring-kafka v3.3.2
- spring-webflux v6.2.2
- spring boot v3.4.2


### Node services

- jsdom v26
- mongodb v6.13.0 
- Node 22.13.1


## Misc 

- nginx v1.27.4





