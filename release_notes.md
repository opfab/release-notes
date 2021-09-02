<!-- Copyright (c) 2018-2021 RTE (http://www.rte-france.com)
 See AUTHORS.txt
 This document is subject to the terms of the Creative Commons Attribution 4.0 International license.
 If a copy of the license was not distributed with this
 file, You can obtain one at https://creativecommons.org/licenses/by/4.0/.
 SPDX-License-Identifier: CC-BY-4.0 -->

# Features

* Card detail view: 
  - #1430 : In card header change the status value -> Card detail header for question cards now displays state type rather than state name
  - #1274 : Add a method for template to get the list of entities allowed to respond
  - #1415 : Add the possibility to use time as axis in chartjs
  - #1444 : Add last response received information on card footer 
* Monitoring :
  - #1248 : Export monitoring : add on option to convert epochdate to date
  - #1407 : Limit the number of lines visible on Monitoring 
* Notification configuration screen :
  - #1263 Add configuration to exclude some states from the notification configuration screen. For more information : https://opfab.github.io/documentation/current/reference_doc/#_configure_the_response_in_config_json
  - #1399 Allow feed notifications to be configured for a whole process
  - #1628 Improve configuration notification screen display when there is a  lot of processes
* Admin screens :
  - #1287 Admin screen : do not display trash icon for admin user line (and ADMIN group) 
  - #1518 Double the width of popups for admin interface 
* Misc :
  - #1453 Prevent setting end date before start date in user card
  - #1266 #1615 Archives UI: see history of a card when clicking on +
  - #1431 Modify current UI behavior when lttd is reached 

# Bugs

* Correct responsive problem with cards examples containing charts (#1479)
* Restore margin for table in admin screens (#1519)
* Correct conditions for allowing acknowledgment (#1504)
* Admin UI : translate placeholder for multi-select component. Add placeholder for single-filter component (#1456)
* Business Period selection for realtime screens - synchronization is incoherent (#1441)
* On startup of the application, sometimes loading in progress appears when no cards are available for user (#1605)
* Persist rabbitMQ consumer queues to be resilient to rabbitMQ restarts (#1669)

# Tasks
* Remove unused btnText field (#1501)
* Remove unused operatorfabric.security.* config in common.yml (#1348)




