swagger: "2.0"
x-collection-name: 123FormBuilder
x-complete: 1
info:
  title: ""
  version: 1.0.0
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