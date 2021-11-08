

# Features



* #1923 #1790 #1818 #1884 #1788 #1789 #1786 #1785 #1782 #1824 #1787 #1784 #1783 #1800 : Remove business data translation mechanism
* #1851 : Admin screen : add an error message when creating a perimeter with an existing id 
* #1918 : Permit log rotation for nginx logs (web-ui)
* #1589 : Monitoring - adding filter for already answered cards
* #1925 : Avoid having to clean browser cache after opfab ui configuration change
* #1819 : Set template.userMemberOfAnEntityRequiredToRespond value for archives card
* #1791 : Make impossible to set the uid field when posting a card
* #1916 : Usercard : Set the possibility to fix lttd via the template code
* #1930 : Remove "service" and "process" columns from the monitoring screen
* #1970 : Do not make a sound for card sent by current user
* #1915 : Add "Emitter" column in the monitoring screen
* #1873 : Authorize sending response from entity emitting user card. Use 'state.response.emittingEntityAllowedToRespond' field in bundle config.json to enable it.
* #1908 : Use user perimeter to present process/state list in UI

# Bugs

* #1821 : Avoid having template.isLocked value to true when displaying an archive card
* #1901 : First day of week does not automatically change in time line when changing language
* #1987 : uiVisibility.monitoring/logging not taken into account for processes without process group
* #1984 : With slow network feed can end up empty after user change notification reception configuration
* #2004 : Usercard restricted recipient list persists when changing process/state
* #2014 : Admin UI : in groups and perimeters tables, edit and delete icons are truncated
* #2005 : Recipients list not well positioned in conference user card
* #2025 : Feedconfiguration screen : wrong display when no process/state for user but bundles exist

# Tasks

* #1286 : web-ui.json : rename parameters `settings.infos.*` as `settings.infos.hide.*`
* #1990 : Add a spinner when loading archives

//TODO : link to documentation for settings 
