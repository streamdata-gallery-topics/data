swagger: "2.0"
x-collection-name: Actility
x-complete: 1
info:
  title: ThingPark DX Maker API
  description: api-providing-features-for-device-makers-such-as-preprovisioning-on-standalone-join-servers-
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /maker/v011/api
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