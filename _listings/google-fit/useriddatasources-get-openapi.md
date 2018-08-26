---
swagger: "2.0"
x-collection-name: Google Fit
x-complete: 0
info:
  title: Google Fit API Get Data Sources
  description: Lists all data sources that are visible to the developer, using the
    OAuth scopes provided. The list is not exhaustive; the user may have private data
    sources that are only visible to other developers, or calls using other scopes.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /fitness/v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{userId}/dataSources:
    get:
      summary: Get Data Sources
      description: Lists all data sources that are visible to the developer, using
        the OAuth scopes provided. The list is not exhaustive; the user may have private
        data sources that are only visible to other developers, or calls using other
        scopes.
      operationId: fitness.users.dataSources.list
      x-api-path-slug: useriddatasources-get
      parameters:
      - in: query
        name: dataTypeName
        description: The names of data types to include in the list
      - in: path
        name: userId
        description: List data sources for the person identified
      responses:
        200:
          description: OK
      tags:
      - Data Source
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---