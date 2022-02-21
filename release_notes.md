# Features
- User cards
     - #1386 : Permit to access edition mode (CREATE or EDITION) from user card template
     - #2498 : In edition mode, give to the template the child card of the current user
     - #2521 : Add the possibility to set startDate via template
     - #2494 : When editing a user card view childcard in preview
- #2467 : Remove timezone management feature
- #2429, #2479 #2480: Add a possibility for user to restrict the list of entities he is connected to
- #2491 : Set default publishDate search period in Archives and Logging screens
- #2519 #2546 : Added ability to deeplink to iFrames (give the possiblity to use subpath when calling business menu), breaking change for redirectToBusinessMenu template method : see [migration documentation](https://opfab.github.io/documentation/archives/3.4.1.RELEASE/docs/single_page_doc.html#_migration_guide_from_release_3_4_0_to_release_3_5_0)
- #2535 : Added Dutch translation
- #2381 : Add the possibility to lock/unlock the visibility domain in the feed and monitoring screens (when lock the visibilty domain does not shift with time)  
- #2567 : Add a remote logging feature (experimental feature) 
- #2427 : Add translation for date picker

# Bugs

- #2449 : The right side of the menus is not visible when the screen size is about 1024 x 600
- #2482 : Bug when in usercard the first process has only one state
- #2451 : Task example usercard : field "minutesForReminder" overwritten by default value when editing the card
- #2462 : Admin perimeter management is not working well when using a non-exising process in perimeter
- #2450 : Monitoring screen - "Card with response form my entity" should be darker color in day mode
- #2455 : Monitoring screen - Problem with padding below "Cards with response from my entities"
- #2454 : Feed : mix between french and english in summary of light card
- #2503 : Problem of html encoding with handlebars
- #2497 : Archives screen : title and summary columns not indented for collapsible archives
- #2539 : Connection not closed when exiting opfab on chrome or edge chromium
- #2506 : Logging screen : set max width on table columns
- #2472 : Card summary and card title showing Hex code instead of special characters
- #2529 : Acknowledge button on new line with screen size 1680*1050
- #2543 : Logrotate for nginx does not work.
- #2558 : No sound on external device when session ended 


# Tasks

- #2505 : Mongo requests for archived cards optimization
- #2456 : Add new user operator5_fr and configure existing users as members ENTITY3_FR and ENTITY4_FR
