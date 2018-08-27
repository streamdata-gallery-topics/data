---
swagger: "2.0"
x-collection-name: 123FormBuilder
x-complete: 0
info:
  title: 123FormBuilder Update group data
  version: 1.0.0
  description: Updates the details of a group.
host: api.123contactform.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /groups/{group_id}:
    put:
      summary: Update group data
      description: Updates the details of a group.
      operationId: updates-the-details-of-a-group
      x-api-path-slug: groupsgroup-id-put
      parameters:
      - in: path
        name: group_id
        description: The ID of the group you want to edit
      - in: formData
        name: JWT
        description: JWT authentication token
      - in: formData
        name: name
        description: This is required when the webhook_url or parent_id is missing
      - in: formData
        name: parent_id
        description: Indicates the ID of the parent group
      - in: formData
        name: webhook_url
        description: This is required when the name or parent_id is missing
      responses:
        200:
          description: OK
      tags:
      - Group
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