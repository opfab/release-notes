# Features

* #2205 : Use publish date to show card on the feed : if card publish date is in user business selected period card will be visible even if card business period does not match with user selected business period.
* #2283 : Adding security to the External Devices API - External devices API should only be accessible to ADMIN users - except notifications endpoint 
* #2296 : Possibility to get entity information and the list of all entities in templates
* #2257 : Permit to access to log api only to members of admin group


# Bugs

* #2268 : Admin screen : words can be cut and displayed in two lines sometimes
* #2277 : Logging export file : bad name of the file
* #2301 : Handling empty configurations for external devices ("Empty" configurations cause Internal Server Error when posting notifications)
* #2269 : Admin screen : filtering on several columns doesn't work
* #2309 : Timeline automatic shifting does not work properly
* #2235 : Admin screen - the popup for the filters is sometimes half hidden


# Tasks

* #2274 : Do not change button name for response on questionState for defaultProcess example
* #2281 : Adding Karate tests for External Devices
* #1946 : Docker recreates volumes every time a docker-compose up is triggered (add a stopOpfab.sh script) 


