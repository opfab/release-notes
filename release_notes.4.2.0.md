
# Features
- #5475 : Rich text editor: highlight active styling buttons
- #5448 : Use badge to show entity recipients for user card preview
- #5432 : In question card build in template add date column for responses
- #5428 : Add a rate limiter for mail sending per destination address
- #5422 : Added the role attribute to entity
- #5595 : Message or question list template - Add option in config file to choose severity
  
# Bugs

- #5489 : Remove default value https://quiljs.com in link edition in rich text editor
- #5485 : Avoid empty line in ag-grid tables
- #5496 : Task advanced : a last comma that should not be displayed
- #5495 : Task advanced : typo error and no uppercase letters for weekdays and months for french version
- #5499 : Fix navbar hovering style in day mode
- #5555 : Reminder shall remove ack at the entity level
- #5567 : Right menu entries shall not be grayed out
- #5474 : Prevent non admin users from accessing the admin screen through the URL
- #5483 : Recurrent card : add a control in the code to forbid negative number for "minutes to remind before task"
- #5295 : Allow to delete card with id containing special characters
- #5482 : Task advanced : the text for a negative number in "nth day of the month" is not right
- #5502 : Business data management tab : missing accents for french version

# Tasks

- Card external diffusion : store in mongoDB mails already sent (#5589)

# Dependencies upgrade

- Angular v17.0.8
- angular-oauth2-oidc v17.0.1
- axios v1.6.3
- chart.js v4.4.1
- Commons-io:commons-io v2.15.1
- com.fasterxml.jackson.core:jackson-annotations v2.16.1
- com.fasterxml.jackson.core:jackson-databind v2.16.1
- com.google.guava:guava v33
- cypress v13.6.2
- io.micrometer:micrometer-registry-prometheus v1.12.1
- io.swagger:swagger-codegen-cli v2.4.39
- moment v2.30.1
- moment-timezone v0.5.44
- nodemailer v6.9.8
- ol(openlayer) v8.2.0
- org.apache.commons:commons-lang3 v3.14.0
- org.assertj:assertj-core v3.25.1
- org.slf4j:slf4j-api v2.0.10
- Rabbitmq Docker v3.12.10
- rrule v2.8.1
- Spring boot v3.2.1
- Spring Kafka v3.1.1
- Spring Security v6.2.1
- Spring Webflux v6.1.2
- types/node v20.10.6
- typescript-eslint monorepo v6.17.0
