# Features

- #2092 : Add the possibility to set entityAllowedToRespond and entitiesRequiredToRespond in usercard template
- #2357 : Add an admin screen to configure external devices for users
- #2360 : Inform template when rendering is done (via method templateGateway.onTemplateRenderingComplete())
- #2386 : Add 'labels' field to Entity model to allow associate labels to an entity
- #2356, #2387, #2355, #2417: New Real Time Users screen. More information here : https://opfab.github.io/documentation/current/reference_doc/#_real_time_users
- #2401 : Add endpoint to list all versions of a business process
- #2428 : Monitoring column answers : showing only EntitiesRequiredToRespond if present
- #2423 : Improve message in api response when error arise when posting card

# Bugs

- #2407 : If user is in entitiesAllowedToEdit but publisher is external, editing card is not allowed
- #2421 : Close subscription when token expired
- #2400 : When using a non existing state in perimeter, admin perimeter management is not working well
- #2430 : Exception in console when loading administration screen


# Tasks

- #1324 : Added Kafka example configurations to documentation
- #2342 : Update test scripts to work on macOS out of the box
- #2354 : Modify examples users and entities
- #2370 : Provide secure nginx conf when checkAuthenticationForCardSending is set to false
- #2238 : Add controls on tasks times when creating user card task example
