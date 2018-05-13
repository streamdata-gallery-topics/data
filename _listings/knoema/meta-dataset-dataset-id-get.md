---
swagger: "2.0"
info:
  title: Knoema API Dataset details
  description: Lists out details of a particular dataset.
  version: 1.0.0
host: knoema.com
basePath: /api/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /meta/dataset/{dataset id}:
    get:
      summary: Dataset details
      description: Lists out details of a particular dataset
      operationId: datasetDetails
      responses:
        200:
          description: OK
      tags:
      - datasets
definitions: []
x-collection-name: Knoema
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