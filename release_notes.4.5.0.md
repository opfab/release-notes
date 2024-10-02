
# Features

- #6814 : Do not permit to send child card of child card
- #6854 : User action logs: add CLOSE_SUBSCRIPTION in action filter
- #6841 : Opfab Cli : Add a command to execute a list of cli commands
- #6531 : Allow to load a custom handlebars helpers file
- #6753 : Set as impossible to load a perimeter with no right field
- #6863 : Don't display confirmation pop up if no changes have been made
- #6881 : Interval between sound should be better controlled in settings screen
- #7102 : Add a confirmation message when business data file is loaded
- #6858 : Prevented saving invalid settings by exiting the settings screen
- #7124 : Send mail even if card has been read
- #6729 : Add three dots and dropdown text when too many entities in acknowledgment footer
- #7230 : Add entities answers popover in card header
- #7017 : Add opfab.alertMessage API
- #7277 : Improve file completion of Opfab CLI
- #6848 : Add opfab cli completion in docker cli
- #7236 : Opfab cli : add a command to add/remove a user from an entity
- #7235 : Opfab cli : add a command to add/remove a user from a group
- #7238 : Opfab cli : add a command to delete a user
- #7237 : Opfab cli : add a command to load a list of users
- #7293 : Opfab cli : add a command to set or unset an activity area

# Bug Fixes

- #6914 : "Publish from" field is reset in archives screen when clicking on "See only the cards I am recipient of"
- #6924 : Show an error in settings if an email checkbox is set and no email address is provided
- #6878 : Do not show "create copy" if user is not allowed to send card
- #6870 : Task advanced : Add a control on negative numbers
- #6998 : Settings screen: "Interval between sound replays" is set to 5 when entering a string on firefox
- #7039 : Monitoring processus screen : fields not in default config are not displayed
- #6829 : Json format check when loading business data is not working
- #6866 : Top border line of rich text editor component thicker than other
- #6865 : Fix geolocalization link when card detail is open
- #7139 : Mail notification configuration not available when only daily mail selected

# Tasks

- #6901 : Unused field in CardDeletionService
- #6828 : Remove spring logs when bad request to card consultation service
- #6847 : Add consistent response for log level on cli
- #6979 : Github actions : Fix docker-compose command not found. Upgrade to docker compose v2
- #6877 : ReadOnly group renamed Maintainer group to avoid confusion
- #6895 : Replace moment.js with date-fns in timeline
- #6876 : Cards Reminder: modify log message when a card is deleted
- #7215 : Implement ui lazy loading
- #6734 : Move monitoring process configuration in a specific configuration file loaded via businessconfig API

# Dependencies upgrade

## Frontend

- ag-grid v32.1.0
- Angular v18.2.5
- chart.js v4.4.4
- date-fns v4 
- date-fns-tz v3.2.0
- ng-bootstrap v17.0.1
- ol v10.2.0
- virtual-select-plugin v1.0.45
- zone.js v0.14.10
  
## Backend 

### Java services 

- avro v1.12.0
- amqp-client v5.22.0
- commons-compress v1.27.1
- commons-io v2.17.0
- commons-lang3 v3.17.0
- com.fasterxml.jackson.core:jackson-databind v2.18.0
- confluent v7.7.1
- date-fns v4 
- date-fns-tz v3.2.0
- guava v33.3.1-jre
- kafka-avro-serializer v7.7.0
- kafka-clients v7.7.0-ce
- kafka-schema-registry-client v7.7.0
- micrometer-registry-prometheus v1.13.4
- ol v10.0.0
- slf4j-api v2.0.16
- spring boot v3.3.4
- spring-kafka v3.2.4
- spring security v6.3.3
- spring-webflux v6.1.13

### Node services

- axios v1.7.7
- express v4.21.0
- Jsdom v25.0.1
- mongodb v6.9.0
- node v20.17.0
- nodemailer v6.9.15
- rimraf v6.0.1
- winston v3.14.2

## Misc 

- nginx v1.27.1
- rabbitmq v4.0.2
- mongodb v7.0.14




