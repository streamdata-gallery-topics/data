---
swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 0
info:
  title: Capital One DevExchange Delete data associated with your API key.
  description: This endpoint deletes any data associated with your API key and of
    the type passed in as query parameters.  If you do not specify any type to delete,
    no data will be deleted.
  version: 1.0.0
host: api.reimaginebanking.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /data:
    delete:
      summary: Delete data associated with your API key.
      description: This endpoint deletes any data associated with your API key and
        of the type passed in as query parameters.  If you do not specify any type
        to delete, no data will be deleted.
      operationId: this-endpoint-deletes-any-data-associated-with-your-api-key-and-of-the-type-passed-in-as-query-param
      x-api-path-slug: data-delete
      parameters:
      - in: query
        name: type
        description: Collection to delete data from
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Data
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