# Migration from 3.11.x

See [Migration Guide from release 3.11.x to release 3.12.0](https://opfab.github.io/documentation/archives/3.12.0.RELEASE/docs/single_page_doc.html#_migration_guide_from_release_3_11_x_to_release_3_12_0)

# Features

- #3717 : Add business logs
- #3731 : Do not show unacknowledgment button when ack is at the entity level
- #3776 : Add in archives footer card detail the entity recipients
- #3768 : Search filter in the Card Feed
- #3884 : Add an option to have no keepAlive for connections to external devices
- #3888 : Open only one connection to a physical external device
- #3793 : Logging: add search filters on title and summary columns
- #3762 : Automatic deletion of cards after an expiration date time has been reached
- #3959 : Map the JWT custom name field to the family_name field
- #3618 : Disabled the pop up button if no entities are selected when responding to a card
- #3627 : Added the pop up text when hovering the response arrow in the monitoring feed
- #4006 : Add a permission mechanism 
- #4008 : Set autofocus on OK button in admin confirmation popups
- #3773 : New reminder feature using RFC 5545 recurrence structure
- #4063 : Do not show menu when user has not the good permission

# Bugs
- #3829 : Monitoring : wrong label in multiselect for service when process groups not totally configured
- #3800 : Monitoring : message when no result should be like the one for archives and logging pages
- #3818 : Admin screens, dots after edit button
- #3824 : Pinned cards : error log in console with reduced view
- #3752 : Entity acknowledgment should mark the card as acknowledged for all users of the entity
- #3831 : Problem with "active from/to" and "publish from/to" dates in archives/logging screens
- #3854 : Cannot add user external device config when slow network
- #3825 : The arrow from the grouped cards symbol would appear even though there are no grouped cards due to the filter settings.
- #3950 : Fix reset button does not clear tags filter in Archives page
- #3848 : Deeplink iFrame link bug
- #3375 : Lock answer in archived cards detail
- #4062 : Fix error in console when opening card with no childs from Archives screen
- #4087 : Admin users : field "authorizedIPAddresses" not taken into account

# Tasks

- #3931 : Archives: fetch archived cards using ArchivedCardsFilter
- #3915 : External app : changing the type of the returned object
- #3628 : Removed padding on column headers for the loggings screen
- #3911 : Update dependency chart.js to v4
- #3993 : Add a new example for getting started
- #4002 : Upgrade Keycloak and MongoDB 
- #2730 : Remove deprecated method templateGateway.getSpecificCardInformation()

