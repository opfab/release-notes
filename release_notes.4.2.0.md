
# Features
- #5475 : Rich text editor: highlight active styling buttons
- #5448 : Use badge to show entity recipients for user card preview
- #5432 : In question card build in template add date column for responses
- #5428 : Add a rate limiter for mail sending per destination address
- #5422 : Added the role attribute to entity
- #5595 : Message or question list template : Add option in config file to choose severity
- #5488 : Add a tooltip for icon to zoom on geo map
- #5596 : Message or question list template - Add option in config file to choose entity publisher list
- #5607 : Added Entity Roles to Activity Area Screen
- #5434 : Entities need the CARD_SENDER role to send a card and the CARD_RECEIVER role to receive a card
- #5614 : Removed entityNotAllowedToSendCard attribute
- #5707 : Added the ACTIVITY_AREA role
- #5461 : Add actions field to Card. Handle PROPAGATE_READ_ACK_TO_PARENT_CARD action
- #5722 : Add "task title" field in task advanced build in template
- #5727 : Added the email template as a config property
- #5748 : Message buildin template : add a field "title of the message"
- #4791 : Remove deprecated methods in templateGateway / usercardTemplateGateway
- #5743 : Add new card action KEEP_CHILD_CARDS to replace keepChildCards
- #5737 : Add rich text editor in message or question list build in template
- #5777 : Add a helper html page to deal with delta quills format (rich text editor format)
- #5729 : Added content of the cards to the mail body
- #5736 : Add the summary as an option in the buildin template of "message or question list" usercard
- #5491 : Activity area : show a message when user has no activity area
- #5738 : Add the option to configure rich text in config file for message or question list build-in template
- #5049 : Implement cancel ack at the entity level
  
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
- #5652 : Archives/loggging screen : disable admin mode shall reset the search result if admin has no processes
- #5617 : Cards reminder error when Task advanced card has "nth day of month" field greater than month number of days
- #5728 : Fix isAcknowledgmentAllowed() method

# Tasks

- #5589 : Card external diffusion : store in mongoDB mails already sent (#5589)
- #5615 : Added a migration script for entity roles
- #5069 : Load test on SSE connection

# Dependencies upgrade

- Angular v17.1.1
- angular-oauth2-oidc v17.0.1
- axios v1.6.7
- chart.js v4.4.1
- config (js) to v3.3.10
- confluent to v7.5.3
- Commons-io:commons-io v2.15.1
- com.fasterxml.jackson.core:jackson-databind v2.16.1
- com.google.guava:guava v33
- cypress v13.6.2
- io.micrometer:micrometer-registry-prometheus v1.12.2
- moment v2.30.1
- moment-timezone v0.5.44
- Node.js v20.11.0
- nodemailer v6.9.9
- ol(openlayer) v8.2.0
- org.apache.commons:commons-lang3 v3.14.0
- org.assertj:assertj-core v3.25.1
- org.slf4j:slf4j-api v2.0.11
- Rabbitmq Docker v3.12.12
- rrule v2.8.1
- Spring boot v3.2.2
- Spring Kafka v3.1.1
- Spring Security v6.2.1
- Spring Webflux v6.1.3
- virtual-select-plugin v1.0.41
- zone.js v0.14.3

