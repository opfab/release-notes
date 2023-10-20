
# Features

- #5058 : Added recipients for information in message or question list
- #4751 : Added advanced task as a built-in template
- #5029 : Add healthcheck endpoint for node services
- #5103 Added an API endpoint to reset rate limiter


# Bugs

- #5129 : Avoid never ending spinner if a request to archives fails
- #5144 : Avoid latency when receiving cards
- #5115 : Remove border in opfab table
- #5169 : Fix search in the Card Feed when the translatedSummary is missing
- #5102 : Avoid truncated pinned cards
- #5101 : Fix Automatic full screen mode for card detail in feed when filters visible
- #5112 : Question usercard : it should be impossible to set a lttd anterior to the current date
- #5120 : Exception in console when geographical map activated
- #5177 : Updated the file size limit of uploads to 100 MB


# Tasks

- #5116 : Add a script to load supervisor configuration
- #5117 : Added coordinates to some example cards for richer view on the map
- #5206 : Set /var/log/opfab as log directory in all node-service dockers
- #4009 : Migrate to keycloak quarkus
