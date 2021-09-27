

# Features
* Monitoring screen : 
  * #1681 Add spinner when loading cards 
  * #1267 Add advance table 
  * #1682 Add an "export in progress" popup when export data 
  * #1743 Apply the sort to the export file
* #1639 Add a response when creating card with API 
* #1647 Add getDisplayContext() method to the template to know in which context the rendering is done
* #1445 Add opfab style for color warning, alert and success
* #1645 Add a method for template to get the entity used for response
* #1429 Add state column to logging screen. Group states by process in multiselect.
* #1736 Notification configuration screen : add a checkbox for filtering by processGroup
* #1761 Archives screen : Add an option to activate / desactivate collapsible updates
* #1774 Add option to store card only in archives DB
* #1807 Add entity name in top-right of the screen
* #1762 Sort by alphabetical order state / process filters in archives/logging screen
* #1804 In card detail header sort the entities to respond by name

# Bugs

* #1677 Do not show popover when lttd expired icon is not visible
* #1700 Fix lttd expired message in card detail
* #1678 Process name not translated in monitoring screen when no process group defined
* #1680 Charts not well display in archives screen
* #1715 Check perimeters existence on group creation or update
* #1547 Error messages and status are mixed up in ExternalAppClientImpl
* #1770 Wrong display when setting a process with only state having "isOnlyAChildState" set to true
* #1777 Default value for acknowledgmentAllowed is not coherent with documentation
* #1813 Optimization to avoid OutOfMemory or mongoDB exception using archive screen

# Tasks

* #1270 Synchronize JWT token data with database
* #1729 Optimize light cards loading when browser is slow
