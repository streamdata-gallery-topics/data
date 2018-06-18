---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Update column data
  description: Update column data.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/custom_gradebook_columns/id/data:
    get:
      summary: List entries for a column
      description: List entries for a column.
      operationId: list-entries-for-a-column
      x-api-path-slug: coursescourse-idcustom-gradebook-columnsiddata-get
      parameters:
      - in: query
        name: include_hidden
        description: If true, hidden columns will be included in the result
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Custom
      - Gradebook
      - Columns
      - Id
      - Data
  /courses/{course_id}/custom_gradebook_columns/id/data/{user_id}:
    put:
      summary: Update column data
      description: Update column data.
      operationId: update-column-data
      x-api-path-slug: coursescourse-idcustom-gradebook-columnsiddatauser-id-put
      parameters:
      - in: query
        name: column_data[content]
        description: Column content
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Custom
      - Gradebook
      - Columns
      - Id
      - Data
      - User
      - Id
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