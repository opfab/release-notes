# Features

- #4442, #4706 : Add a more customizable navigation bar menu
- #4396, #4712 : Add a service to send card reception alerte via mail (cards-external-diffusion service)
- #4448 : Create usercard as a copy
- #4546 : Add a message if the user has no process/state in the dashboard
- #4447 : Add connection status circle next to entities in card preview
- #4438 : Opfab API V1
- #3629 : Optimize grouping feed feature when a lot of cards are present
- #4607 : Add reload page button to the application-loading screen
- #4596 : Remove "Write" right for perimeters
- #4451 : If navigation bar menu has only one entry, show submenu anyway
- #4640 : Do not authorize space in login and minimum length 2 characters
- #4320 : Add a ui screen to manage buisness data file
- #4449 : Add a supervisor for connections and not acknowledged cards (supervisor service)
- #4641 : When adding or editing a user, it's possible to see, add or edit a comment about the user
- #4669 : No longer consider case when checking login is equal to publisher / representative for card sending
- #4764 : Added the option 'hideBusinessMessages' to web-ui.json to hide alert messages with level 'BUSINESS'and renamed and moved alertMessageBusinessAutoClose and alertMessageOnBottomOfTheScreen to a new alerts section in the config
- #4727 : Titles of cards in the front are truncated if too long
- #4329 : Rate limiter for card sending
- #4776 : Add a tooltip to show user connected entities
- #4368 : In archives view / export : removed field business period, added fields publisher, entity recipients and process
- #4884 : Add business period in card footer for archives detail card
- #4632 : Grouped cards : blue arrow should not be displayed if only one card
- #4948 : Permit to send geo information from a user card
- #4794 : Add the possibility to set the publisher of the card via getUserResponse
- #4518 : Add a tooltip component for template or external apps
- #4963 : Add methods userCardTemplate.setSelectedRecipients and userCardTemplate.setSelectedRecipientsForInformation
- #4900 : Realtime screen : only show users member of specific groups
- #4752 Added message selection from a JSON file as a built-in template


# Bugs

- #4539 : Geomap disappears if we update a card (via edit button)
- #4540 : Default value set in "recipients in copy" field in edit mode
- #4542 : Dashboard : unexpected redirection to the feed after editing and updating a card
- #4536 : Fix datepicker reset
- #4537 : Removed scrollbar and fullscreen button from dashboard cards
- #4533 : Fixed the date format when 'Day' is selected on the timeline while hidden
- #4691 : Error in the formating of delete confirmation for the admin table in dutch
- #4946 : Fix External application theme when opened in new tab


# Tasks

 - #4454 : Add scripts to change log level on services
 - #4586, #4732 : Transfer card reminder management from ui to backend (cards-reminder service)
 - #4687 : Simplify opfab configuration
 - #4704 : Migrate to java 17.0.8
 - #4689 : Add a mongoDB index for field parentCardId (in cards and in archives)
 - #4834 : Simplify endpoints configuration in UI
 - #4914 : Update dependency chart.js to v4.4.0
 - #4738 : Load processes with all versions on ui startup
 - #4984 : Prevent log injection
 - #4922 : Create an operatorfabric docker for RabbitMQ to fix rabbit version
 - #4945 : Rename external recipients config params
 - #5030 : Close eventStream when session is really expired
