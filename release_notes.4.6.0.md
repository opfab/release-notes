
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

# Tasks

- #7554 : Rename timeline domain TR to RT (Real Time)

# Dependencies upgrade

## Frontend

- ag-grid v32.3.3
- angular 18.2.13
- chart.js v4.4.6
- fortawesome/fontawesome-free v6.7.1
- ngx-translate/core v16.0.3
- swimlane/ngx-charts v21.0.0
  
## Backend 

### Java services 

- commons-io v2.18.0
- jackson-annotations v2.18.1
- jackson-databind to v2.18.1
- micrometer-registry-prometheus v1.14.1
- rabbitmq:amqp-client v5.23.0
- spring boot v3.3.5
- spring security v6.4.1
- spring-webflux to v6.2.0

### Node services
- amqplib to v0.10.5
- axios v1.7.8
- node v22.11.0
- nodemailer v6.9.16
- mongodb v6.10.0
- winston v3.17.0

## Misc 

-  rabbitmq Docker v4.0.4
-  nginx Docker v1.27.3




