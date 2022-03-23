# Features

- #2594 : Added Dutch translation for date picker
- #2526 : Usercard : permit to choose the entity that publish if more than one is possible for the current user
- #2493 : Usercard : add the access to the current process and state in user card templates
- #2527 : Card response : permit the user to choose entity when responding to a card
- #2584 : Enable to set temporarily startDate after endDate during userCard creation
- #2595 : Allow user to filter by process without choosing a process group in archives, monitoring and logging screens
- #2665 : Remove unused feature business logs
- #2574 : Display disabled buttons in gray in pagination
- #2495 : Add method in userTemplateGateway to set/get startDate,endDate, lttd
- #2673 : In usercard screen, show process select even if there is only one process
- #2675 : Add a method to tell the usercard template the entity used to send card
- #2670 : Add acknowledgement at the entity level. Now when a user acknowledges a card, he also acknowledges it for his(its) entity(ies).
- #2560 : Add child cards in archive detail cards
- #2712 : Add the possibility for the usercard template to set the list of recipient choices or the list of recipients

# Bugs

- #2593 : Monitoring: ag-grid filter is not localized
- #2585 : Missing ag-grid translation in filter column feature
- #2596 : External devices screen : filter popup sometimes hidden
- #2583 : Feed : card indented whereas it should not
- #2581 : In settings, control the value "Interval between sound replays"
- #2592 : Administration screen : create new user/entity/group with existing id is permitted whereas it should not
- #2582 : In day mode, numbers in bubbles on timeline are not always fully visible
- #2140 : Fix card publishing path in nginx-cors-permissive.conf
- #2689 : Limit custom logo height to 48px (the parameter logo.limitSize in web-ui.json is not used anymore) to avoid hiding part of the ui.
- #2705 : Add error message instead of spinner when error in logging/archives screen

# Tasks

- #2586 : Add information about minimum resolution to use OperatorFabric
- #2587 : Add remoteLoggingEnabled UI parameters in documentation
- #2459 : Entity labels : Add label with no need for the user to click enter
- #2573 : Add entity name in templates example instead of entityId
- #2578 : Add opfab version in package.json and use it for the about screen
- #2557 : Start even if translation file is not present for a declared language
- #1305 : Ensure version consistence by relying entirely on Gradle wrapper for building
- #2659 : Adding cypress tests for export file in archives and logging screens
- #2577 : Transfert method getSpecificCardInformation from templateGateway to usercardTemplateGateway (use of templateGateway.getSpecificCardInformation is now deprecated)
- #2715 : improve ui log library
