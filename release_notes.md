# Features

* #2126 : Admin screen : Use state names instead of state ids for perimeter screens
* #1991 : Add a spinner when loading logging cards
* #2181 : Add checkbox to apply filters to timeline or not
* #2145 : Put scrollbar of administration modals directly in modals
* #2197 : Remove unused tag feature
* #1646 : Permit multiple entity to edit the same card
* #2127 : Make editable the labels of the validation/edition buttons of the reponse according to the "State"
* #2195 : Improve external devices configuration management API
* #2209 : Offer the possiblity to hide the recipient list in usercard

# Bugs

* #2136 : Monitoring screen - Answers filtering based on id instead of name
* #2028 : Admin screen - pagination and displayed results not coherent after a delete
* #2137 : Archives screen : spinner almost hidden when already displayed results
* #2184 : Usercard update : startDate and endDate overwritten with default value
* #2171 : Monitoring : The sort by severity doesn't work anymore
* #2144 : Admin screen : remove empty space in array of users/groups/entities/perimeters
* #2133 : In usercard sometimes lttd is after enddate
* #2240 : Correct bug in usercard when using same stateId in different processes
* #2141 : Fitlering column State Rights in perimeter management screen is not working
* #2236 : Perimeters management UI : sorting on State Rights column is not good
* #2243 : Editing a received card "breaks" subsequent sound notifications
* #2029 : Instance-wide default values mechanism for settings properties can be confusing
* #2271 : Monitoring screen: Missing '-' between startDate and endDate in column business period in export file
* #2289 : Sound activation improvements . Using chromium based browser, when reloading the application (via F5 for example) the sound is only activated if user interact with the application (due to autoplay policy ). This correction force the user to click on the page to activate the sound if the case arise

# Tasks

* #2155 : Publish documentation for the external devices API to website
* #2156 : Set up publication of client jar for external devices in build
* #2170 : Do not cache i18n files to avoid the user having to clean his cache when upgrading opfab
* #2161 : Add the external devices service & dummies to default docker-compose
* #2054 : Update to Angular v13
* #2104 : UI - Deal with delete child card



