---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Table Data Body Range
  description: 'Table: DataBodyRange Gets the range object associated with the data
    body of the table.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/tables(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Data Body Range
      description: 'Table: DataBodyRange Gets the range object associated with the
        data body of the table.'
      operationId: Table:DataBodyRange
      x-api-path-slug: workbooktablesltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Data
      - Body
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Data Body Range
      description: 'Table: DataBodyRange Gets the range object associated with the
        data body of the table.'
      operationId: Table:DataBodyRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Data
      - Body
      - Range
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