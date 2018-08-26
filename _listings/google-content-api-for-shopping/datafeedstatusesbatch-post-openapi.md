---
swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 0
info:
  title: Google Content API for Shopping API Data Feed Status
  description: Retrieves data feed batch status.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /content/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /datafeeds/batch:
    post:
      summary: Data Feeds
      description: Retrieves data feed batches.
      operationId: content.datafeeds.custombatch
      x-api-path-slug: datafeedsbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Data
      - Feeds
  /datafeedstatuses/batch:
    post:
      summary: Data Feed Status
      description: Retrieves data feed batch status.
      operationId: content.datafeedstatuses.custombatch
      x-api-path-slug: datafeedstatusesbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Data
      - Feed
      - Status
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