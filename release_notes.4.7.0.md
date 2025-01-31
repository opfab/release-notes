
# Features

- #7787 : Add vertical scrolling inside array in admin screens
- #7592 : Add an API frontend method to send response card
- #7706 : Add the possibility to send card on behalf of user instead of entity
- #7847 : Add first name and last name on real time screen instead of login
- #7850 : Add possibility to hide publisher multiselect in usercard
- #7876 : Add first name and last name of user on activity area screen
- #7877 : Add an option to not received card details
- #7708 : Add support for loading custom global CSS
- #7881 : Add the possibility to define custom card list screens


# Bug Fixes

- #7803 In archives card display edit button shall never appears in message card example
- #7867 Fixed long state names in notification configuration
- #7851 cli : "opfab help commands" does not work



# Tasks

- #7826 : Avoid security log in cards-publication service on startup
- #7878 : Defined charset to UTF-8 in when saving process monitoring file

# Dependencies upgrade

## Frontend

- virtual-select-plugin v1.0.47
- ngx-charts v21.1.3 
  
## Backend 

### Java services 

- micrometer-registry-prometheus 1.14.3
- org.apache.commons:commons-pool2 2.12.1
- spring-kafka v3.3.2
- spring-webflux v6.2.2


### Node services

- jsdom v26
- Node 22.13.1


## Misc 







