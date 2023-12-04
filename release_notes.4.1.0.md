
# Features

- #5058 : Added recipients for information in message or question list
- #4751 : Added advanced task as a built-in template
- #5029 : Added healthcheck endpoint for node services
- #5103 : Added an API endpoint to reset rate limiter
- #5056 : Added a permission VIEW_ALL_ARCHIVED_CARDS_FOR_USER_PERIMETERS
- #4697 : Process monitoring screen - experimental feature
- #5108 : Preview of users connected takes notification configuration into account
- #5312 : The API now allows to call all the entities the user can answer on behalf of
- #5028 : Add an admin screen for supervisor
- #5375 : Use rich text editor in message build in templates
- #5436 : Removed the type attribute of groups
- #5490 : Task advanced : make impossible a card without any month/weekday selected
- #5486 : Fix admin screen missing translations


# Bugs

- #5129 : Avoid never ending spinner if a request to archives fails
- #5144 : Avoid latency when receiving cards
- #5115 : Remove border in opfab table
- #5169 : Fix search in the Card Feed when the translatedSummary is missing
- #5102 : Avoid truncated pinned cards
- #5101 : Fix Automatic full screen mode for card detail in feed when filters visible
- #5112 : Question usercard : it should be impossible to set a lttd anterior to the current date
- #5120 : Exception in console when geographical map activated
- #5177 : Updated the file size limit of uploads to 100 MB
- #5253 : Do not group cards that have no tag set
- #5145 : Activity areas can bypass restriction on emitting entity allowed to respond
- #5310 : Correct various bug in card reminder
- #5334 : Fix bug on buildin template task, for task description field
- #5110 : Opening a card from dashboard now closes the tooltip
- #5389 : Fixed the message-or-question-list message selection
- #5343 : Popover tooltips from the colored circles of timeline and dashboard don't appear or disappear properly
- #5481 : Task advanced : in the template, it should be impossible to set a negative number in "task duration" and "minutes to remind before task"
- #5546 : No reminder occurs when secondsBeforeTimeSpanForReminder is set to 0


# Tasks

- #5116 : Add a script to load supervisor configuration
- #5117 : Added coordinates to some example cards for richer view on the map
- #5206 : Set /var/log/opfab as log directory in all node-service dockers
- #4009 : Migrate to keycloak quarkus
- #5319 : Add scripts to help dependency analysis
- #5440 : Add an index on mongoDB archivedCards collection for field processInstanceId