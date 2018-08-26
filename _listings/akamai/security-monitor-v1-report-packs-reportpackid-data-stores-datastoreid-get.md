---
swagger: "2.0"
info:
  title: Akamai API Get a Data Store
  description: Get a Data Store
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /security-monitor/v1/report-packs/{reportPackId}/data-stores/{dataStoreId}:
    get:
      summary: Get a Data Store
      description: Get a Data Store
      operationId: securitymonitorv1reportpacksreportpackiddatastoresdatastoreid
      parameters:
      - in: query
        name: dataStoreId
        description: Data store ID
        type: string
      - in: query
        name: reportPackId
        description: Report pack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - security
      - monitor
      - report
      - packs
      - reportpack
      - data
      - stores
      - datastore
definitions: []
x-collection-name: Akamai
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