
# Features
- #7335 : Opfab Cli - Add a command line to start or stop the supervisor service
- #7339 : Add a user action log when user change notification configuration
- #7446 : Localized error message when impossible to send alarm signal to external device
- #7447 : Replace toNotify field with STORE_ONLY_IN_ARCHIVES card Action

# Bug Fixes
- #7418 : Check for entity name in the entity creation form doesn't handle empty spaces
- #7411 : It should not be possible to set string in "Interval between sound" in settings
- #7427 : UserCard: do not show "Create copy" button if user not allowed to publish the card
- #7413 : User action logs : close popover when clicking on link in card detail
- #7414 : No entities in ack visible if one entity is not existing
- #7425 : Archives/Logging screens : display error if there is no process group and no tag

# Tasks


# Dependencies upgrade

## Frontend

- ag-grid 32.3.2
  
## Backend 

### Java services 

- jackson-annotations v2.18.1
- micrometer-registry-prometheus 1.13.6
- spring boot 3.3.5
- spring security 6.3.4
- spring-webflux 6.1.14

### Node services


## Misc 






