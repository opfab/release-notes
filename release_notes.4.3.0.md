
# Features

- #5792 : Remove deprecated use of group admin to set the admin rights
- #5921 : Do not try again to send mail for user rate limited
- #5869 : Add logLevel endpoint for node services
- #5870 : Add the possibility to manage user group membership in the group creation/modification screen
- #5871 : Add the ability to manage user entity membership in the entity creation/modification screen
- #5612 : Add an option to set the default opfab entry page
- #5948 : Propose to save when exiting notification configuration screen
- #4249 : Replace current date picker with standard date picker of browser
- #5949 : Allow to add new external devices from UI
- #5951 : Add a delete button to delete an external device configuration
- #6032 : Add an export button for "user action logs" screen
- #5733 : Added the option to send daily recap by email
- #5878 : Permit to render rich text in mail body via a handlebar helper
- #6023 : Do not save automatically settings
- #6021 : Add multiple geopmap layers
- #6013 : Added warning in the UI in case of cycle in parent entity references
- #5821 : Geopmap geojson layers: configure custom style
- #6167 : Search for entities when creating supervised entities enabled
  
# Bug Fixes

- #6020 : Geopmap geojson layer : deactivate infobubble on click if no information to display
- #6123 : Fixed color of time filter in feed
- #5904 : Turned off email autocomplete to fix styling bug
- #5906 : Fixed sorting of entities in admin tables
- #6170 : Supervisor: fix Supervised Entity Not Deleted Until Service Restart
- #5902 : Fix login input cursor color
- #6156 : User action logs menu is not limited by ADMIN role anymore

# Tasks
- #6079: Remove legacy field realtime in group object
- #6026 : Add a geojson example
- #6115 : Add path controls in PathUtils to mitigate path manipulation vulnerabilities

# Dependencies upgrade

- ag-grid-angular v31.1.1
- ag-grid-community v31.1.1
- Angular v17.3.2
- axios v1.6.8
- bootstrap v5.3.3
- chart.js v4.4.2
- Confluent v7.6.0
- com.fasterxml.jackson.core:jackson-databind v2.17.0
- com.fasterxml.jackson.core:jackson-annotations to v2.17.0
- com.github.jknack:handlebars v4.4.0
- com.google.guava:guava v33.1.0-jre
- express v4.19.2
- io.micrometer:micrometer-registry-prometheus v1.12.4
- moment-timezone to v0.5.45
- mongodb (npm package) v6.5.0
- net.minidev:json-smart v2.5.1
- nginx v1.25.4
- Node.js v20.11.1
- nodemailer v6.9.13
- ol v9.0.0
- openjdk v17.0.10
- org.apache.commons:commons-compress v1.26.1
- org.slf4j:slf4j-api v2.0.12
- org.springframework:spring-webflux v6.1.5
- spring boot v3.2.4
- spring kafka v3.1.3
- spring security v6.2.3
- typescript to v5.4.3
- rabbitmq v3.13.0
- winston v3.13.0
- winston-daily-rotate-file v5
- zone.js v0.14.4



