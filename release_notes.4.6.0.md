
# Features

- Archives and logging screens :
  - #7551 : Permit to choose the number of line to display
  - #7625 : Add vertical scrollbar to Archive screen
  - #7783 : Add vertical scrollbar to Logging screen
  - #7267, #7710: Add a date range picker
- Emails :
  - #7663 : Added body prefix to recap emails
  - #7664 : Added body postfix to recap emails
  - #7564 : Permit to receive mail for not notified state in UI
  - #5734 : Add an option to receive a weekly email recap
  - #7653 : Permit to configure Timezone
  - #7699 : Add the possiblity to access config parameters in handlebars mail template
- Cli :
  - #7335 : Add a command line to start or stop the supervisor service
  - #7448 : See all connected users via the cli
- Opfab API :
  - #7565 : Add a method to get the current visible period
  - #7566 : Add a method to get a list of cards
- User cards  :
  - #7588 : Add the list of child entities in recipient and recipient for information multiselect
  - #7651 : Usercard preview : show child entities as tooltip
  - #7705 : Add the possibility to set field groupRecipients when sending user card
- Card detail :
  - #7498 : Allow to create a popup in a card
  - #7525 : Add the possibility to have a button to edit card
- Misc :    
  - #7339 : Add a user action log when user change notification configuration
  - #7446 : Localized error message when impossible to send alarm signal to external device
  - #7447, #7480 : Replace toNotify field with STORE_ONLY_IN_ARCHIVES card Action
  - #7386 : Add setting to open next card on acknowledgment
  - #7547 : Dashboard - Add a link to business menu for certain process/states
  - #7662 : Add entity ID in entity selection for admin screens
  - #7761 : Homogenize number of lines for table multiselect position


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
- #7680 : Wrong dates send to external recipients
- #7665 : Took daylight savings time into account for recap emails
- #7811 : Opfab-cli : "opfab get log-level" for external-devices failed

# Tasks

- #7554 : Rename timeline domain TR to RT (Real Time)
- #7499 : Remove field "timespans.recurrence" in opfab

# Dependencies upgrade

## Frontend

- ag-grid 32.3.3
- angular 18.2.13
- chart.js 4.4.7
- fortawesome/fontawesome-free 6.7.2
- ngx-translate/core 16.0.4
- quill 2.0.3
- swimlane/ngx-charts 21.1.2
  
## Backend 

### Java services 

- confluent 7.8.0
- com.google.guava:guava v33.4.0-jre
- commons-io 2.18.0 
- commons-text v1.13.0
- jackson-annotations 2.18.2 
- jackson-databind to 2.18.2
- micrometer-registry-prometheus 1.14.2
- rabbitmq:amqp-client 5.24.0
- spring boot 3.4.1
- springKafka 3.3.1
- spring security 6.4.2
- spring-webflux to 6.2.1

### Node services

- amqplib to 0.10.5
- axios 1.7.9
- express 4.21.2
- express-jwt 8.5.1
- mongodb 6.12.0
- node 22.13.1
- nodemailer 6.9.16
- winston 3.17.0

## Misc 

- mongo v7.0.16
- nginx Docker 1.27.3
- rabbitmq Docker 4.0.5





