<!-- Copyright (c) 2018-2021 RTE (http://www.rte-france.com)
 See AUTHORS.txt
 This document is subject to the terms of the Creative Commons Attribution 4.0 International license.
 If a copy of the license was not distributed with this
 file, You can obtain one at https://creativecommons.org/licenses/by/4.0/.
 SPDX-License-Identifier: CC-BY-4.0 -->

# Features

* In card header change the status value -> Card detail header for question cards now displays state type rather than state name (#1430)
* Export monitoring : add on option to convert epochdate to date (#1248)
* Add a method for template to get the list of entities allowed to respond (#1274)
* Prevent setting end date before start date in user card (#1453)
* Archives UI: see history of a card when clicking on + (#1266)
* Add configuration to exclude some states from the notification configuration screen (#1263). For more information : https://opfab.github.io/documentation/current/reference_doc/#_configure_the_response_in_config_json
* Modify current UI behavior when lttd is reached (#1431)
* Limit the number of lines visible on Monitoring (#1407)
* Admin screen : do not display trash icon for admin user line (and ADMIN group) (#1287)
* Add the possibility to use time as axis in chartjs (#1415)
* Allow feed notifications to be configured for a whole process (#1399)
* Card detail: add last response received information on card footer (#1444)

# Bugs

* Correct responsive problem with cards examples containing charts (#1479)
* Restore margin for table in admin screens (#1519)
* Correct conditions for allowing acknowledgment (#1504)
* Admin UI : translate placeholder for multi-select component. Add placeholder for single-filter component (#1456)
* Business Period selection for realtime screens - synchronization is incoherent (#1441)
* On startup of the application, sometimes loading in progress appears when no cards are available for user (#1605)

# Tasks
* Remove unused btnText field (#1501)
* Remove unused operatorfabric.security.* config in common.yml (#1348)
* Double the width of popups for admin interface (#1518)

# Dependency updates

NOTE: These are only highlights, not all updated dependencies are listed below.

* Update nginx Docker image used in web-ui to v1.21.1
* Update angular to v12.1.2
* Update angular-oauth2-oidc to v12.0.0


