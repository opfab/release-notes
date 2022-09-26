# Features

- #3357 : Add spinner when changing connected entities in activity area screen
- #3349 : Add a spinner when delete a card if slow network
- #3347 : Add a spinner when logout is slow
- #3149 : Show entities concerned by card in footer
- #3328 : Settings screen configuration : move "settings.infos.hide" section to ''settingsScreen.hiddenSettings"
- #3383 : Permit to select more than one entity if possible when sending a response card
- #3310, #3405 : Provide shared css/js to external applications
- #3408 : User cards: Permit to add a list of recipients via the template & user choice
- #3452 : Add hover and zoom-to-card on the geomap function 
- #3486 : Add remote logs for debugging purpose
- #1328 : Prevent the removal of the administration group for the admin user
- #3299 : Regularly try to reconnect disconnected external devices
- #3234, #3543 : Refuse sending card if process or state does not exist (feature can be desactivate by configuration) 
- #3331 : Add a possibility to have non filterable notifications
- #1318 : Resource identifiers should only contain letters, digits, dashes or underscores
- #3503 : Add export feature for admin screens
- #3450 : Geographical map: add a optional chart to display number of cards by severity
- #3545 : Add a possibility to not close card when user acknowledge
- #3534 : Administration screen : Add in groups popup the list of members
- #3544 : Add the possibility to hide edit or delete card link
- #3565 : Add option to sort cards by start and end date
- #3589 : Add logs when user ack/read/unack/unread
- #3570 : Set default feed filtering and sorting values in web-ui.json
- #3595 : Add methods for templates to set selected values and options list in multiselect component
- #3566 : Add setting to automatically open the first card in list
- #3603 : Administration screen : Add in entity popup the list of members
- #3623 : Feed filters : red color for the icon in case filtering is activated

# Bugs

- #3370 : Feed light card : words are cut in summary text 
- #3169 : Redirection to the feed when editing a card from monitoring/agenda
- #3369 : Cursor is not valid in monitoring table when going over the table rows
- #3355 : Group administration : bad display of TYPE single-select
- #3361 : Admin checkbox : mouseover text overflows the screen
- #3172 : Checkboxes can be checked even outside the text
- #3306 : Remove settings value playSoundOnExternalDevice when removing user link to external device
- #3371 : Cursor not valid in << and >> (monitoring screen and feed when timeline is hidden)
- #3367 : Cursor for "Acknowledge all cards" link is not the good one
- #3368 : Feed : "Reset all filters" link is clickable on more than just the text
- #3350 : Spinner too small when we send a usercard
- #3422 : Not using default sound settings defined in web-ui.json when user has no settings
- #3374 : Bad display of "Response closed" dutch version
- #3435 : Unused fields in request when update/create a perimeter via admin UI
- #3372 : Send HTTP error 500 when external application endpoint is not found
- #3362 : Spinner for loading opfab : use shared spinner component
- #3466 : Group/entity/perimeter creation : some special characters in id field are not forbidden
- #3353 : Logout with slow network show "session expired" popup
- #2998 : No sound on Firefox after closing and reopening the browser
- #3471 : Migration script to opfab 3 : special characters not well translated
- #3488 : Fix pinned cards display for long titles
- #3176 : Updates for users/entities/groups should be sent to components that need it
- #3512 : Realtime screen bug when a connected user has no entity
- #3562 : Admin screens: do not cut long values for ID column

# Tasks

- #3327 : Move the about configuration away from settings in web-ui.json
- #3430 : Update dependency chart.js to v3.8.2
- #3320 : Remove unecessary error management in ui
- #3487 : Reduce space between reponse and ack icons in feed
