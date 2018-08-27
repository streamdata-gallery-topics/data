swagger: "2.0"
x-collection-name: Intrinio
x-complete: 1
info:
  title: Intrinio
  version: 1.0.0
host: api.intrinio.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /data_point:
    get:
      summary: Data Point
      description: Returns the most recent median data point for an Economic index
        for a selected tag.  The complete list of Economic Indices can be found here.  The
        complete list of Economic tags available through this function are available
        here.
      operationId: data-point
      x-api-path-slug: data-point-get
      parameters:
      - in: query
        name: identifier
        description: 'an identifier for the Economic Index selected:'
        type: string
      - in: query
        name: item
        description: 'the specified standardized tag or series ID requested: ECONOMIC
          TAGS'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Data