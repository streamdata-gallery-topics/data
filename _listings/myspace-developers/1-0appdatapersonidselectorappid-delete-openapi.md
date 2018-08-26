---
swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 0
info:
  title: My Space Delete Appdata Personid Selector Appid
  description: Deletes a specified user's application data.
  version: 1.0.0
host: api.myspace.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1.0/appdata/{personId}/{selector}/{appId}:
    delete:
      summary: Delete Appdata Personid Selector Appid
      description: Deletes a specified user's application data.
      operationId: 1.0.appdata.personId.selector.appId.delete
      x-api-path-slug: 1-0appdatapersonidselectorappid-delete
      parameters:
      - in: path
        name: appId
        description: The applications ID associated with the OAuth ConsumerKey/ConsumerSecret
          pair
      - in: query
        name: fields
        description: The fields correspond to keys in the application data
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      responses:
        200:
          description: OK
      tags:
      - Appdata
      - People
      - Selector
      - AppId
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