
# Features
- #7335 : Opfab Cli - Add a command line to start or stop the supervisor service
- #7339 : Add a user action log when user change notification configuration
- #7446 : Localized error message when impossible to send alarm signal to external device
- #7447 : Replace toNotify field with STORE_ONLY_IN_ARCHIVES card Action
- #7386 : Add setting to open next card on acknowledgment
- #7448 : See all connected users via the cli
- #7498 : Allow to create a popup in a card
- #7547 : Dashboard - Add a link to business menu for certain process/states
- #7564 : Permit to receive mail for not notified state in UI
- #7565 : Opfab API : Add a method to get the current visible period
- #7267 : Add a date range picker for archives / logging screens
- #7588 : Add the list of child entities in recipient and recipient for information multiselect
- #7566 : Opfab API : Add a method to get a list of cards
- #7551 : Archives / Logging : permit to choose the number of line to display
- #5734 : Add an option to receive a weekly email recap

# Bug Fixes

- #7152 : Fix archives screen sublines columns width
- #7403 : Missing space in templates if startDate, endDate and severity are not visible
- #7404 : Fix modal style
- #7410 : Opfab cli : fix error message when removing user from group/entity
- #7411 : It should not be possible to set string in "Interval between sound" in settings
- #7413 : User action logs : close popover when clicking on link in card detail
- #7414 : No entities in ack visible if one entity is not existing
- #7418 : Check for entity name in the entity creation form doesn't handle empty spaces
- #7425 : Archives/Logging screens : display error if there is no process group and no tag
- #7427 : UserCard: do not show "Create copy" button if user not allowed to publish the card
- #7526 : Exception in console when editing cards
- #7549 : Fix Supervisor default config value for arrays
- #7571 : Memory leak in regularlyCheckLttd in card
- #7585 : Impossible to change entity name for some entities
- #7632 : Redirection lost when using link provided in opfab email

# Tasks

- #7554 : Rename timeline domain TR to RT (Real Time)

# Dependencies upgrade

## Frontend

- ag-grid 32.3.3
- angular 18.2.13
- chart.js 4.4.6
- fortawesome/fontawesome-free 6.7.1
- ngx-translate/core 16.0.3
- swimlane/ngx-charts 21.0.0
  
## Backend 

### Java services 

- confluent 7.8.0
- commons-io 2.18.0
- jackson-annotations 2.18.2 
- jackson-databind to 2.18.2
- micrometer-registry-prometheus 1.14.1
- rabbitmq:amqp-client 5.23.0
- spring boot 3.3.5
- springKafka 3.3.0
- spring security 6.4.1
- spring-webflux to 6.2.0

### Node services
- amqplib to 0.10.5
- axios 1.7.9
- express 4.21.2
- node 22.11.0
- nodemailer 6.9.16
- mongodb 6.10.0
- winston 3.17.0

## Misc 

-  eslint 9.16.0
-  quill 2.0.3
-  nginx Docker 1.27.3
-  rabbitmq Docker 4.0.4
-  typescript-eslint 8.16.0




