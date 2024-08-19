
# Features

- #6814 : Do not permit to send child card of child card
- #6854 : User action logs: add CLOSE_SUBSCRIPTION in action filter
- #6835 : Added a body postfix to sent emails
- #6841 : Opfab Cli : Add a command to execute a list of cli commands
- #6531 : Allow to load a custom handlebars helpers file
- #6753 : Set as impossible to load a perimeter with no right field
- #6863 : Don't display confirmation pop up if no changes have been made
- #6736 : Update to angular v18, ng-bootstrap v17
- #6881 : Interval between sound should be better controlled in settings screen

# Bug Fixes

- #6914 : "Publish from" field is reset in archives screen when clicking on "See only the cards I am recipient of"
- #6965 : Documentation for registerFunctionToGetTags function is not compliant with the implementation
- #6924 : Show an error in settings if an email checkbox is set and no email address is provided
- #6878 : Do not show "create copy" if user is not allowed to send card
- #6870 : Task advanced : Add a control on negative numbers

# Tasks

- #6901 : Unused field in CardDeletionService
- #6828 : Remove spring logs when bad request to card consultation service
- #6847 : Add consistent response for log level on cli
- #6979 : Github actions : Fix docker-compose command not found. Upgrade to docker compose v2
- #6877 : ReadOnly group renamed Maintainer group to avoid confusion
- #6895 : Replace moment.js with date-fns in timeline
- #6876 : Cards Reminder: modify log message when a card is deleted

# Dependencies upgrade

- actions/upload-artifact v4.3.6
- ag-grid v32.1.0
- Angular v17.3.12
- angular-eslint monorepo v18.3.0
- axios v1.7.4
- com.google.guava:guava v33.3.0-jre
- Confluent v7.6.2
- cypress 13.13.3
- eslint-plugin-prettier v5.2.1
- eslint-plugin-promise v6.6.0
- io.confluent:kafka-avro-serializer v7.7.0
- io.confluent:kafka-schema-registry-client v7.7.0
- io.micrometer:micrometer-registry-prometheus v1.13.3
- io.swagger:swagger-codegen-cli v2.4.43
- jasmine-core v5.2.0
- Jsdom  v24.1.1
- karma v6.4.4
- node v20.16.0
- ol v10.0.0
- org.apache.avro:avro v1.12.0
- org.apache.commons:commons-compress v1.27.0
- org.apache.commons:commons-lang3 v3.16.0
- org.apache.kafka:kafka-clients v7.7.0-ce
- org.slf4j:slf4j-api v2.0.16
- org.springframework:spring-webflux v6.1.12
- ossf/scorecard-action v2.4.0
- Rabbitmq v3.13.6
- rimraf v6.0.1
- Spring-kafka v3.2.2
- Spring boot v3.3.2
- tj-actions/changed-files v44.5.7
- ts-jest v29.2.4
- types/node v20.14.15
- winston v3.14.2
- zone.js v0.14.10
