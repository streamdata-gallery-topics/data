---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Dataflow API Uplink data reception
  description: Endpoint to be used by the LRC to push uplink data in order to use
    ThingPark X dataflows.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /dataflow/v021/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /uplinkMessages:
    post:
      summary: Uplink data reception
      description: Endpoint to be used by the LRC to push uplink data in order to
        use ThingPark X dataflows.
      operationId: endpoint-to-be-used-by-the-lrc-to-push-uplink-data-in-order-to-use-thingpark-x-dataflows
      x-api-path-slug: uplinkmessages-post
      parameters:
      - in: body
        name: data
        description: Uplink data frame in ThingPark XML or JSON format
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Uplink
      - Data
      - Reception
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