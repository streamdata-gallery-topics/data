---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Updates project data
  version: 1.0.0
  description: Updates project data.
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{userid}:
    get:
      summary: Gets user data by user id
      description: Gets user data by user id.
      operationId: getUserById
      x-api-path-slug: usersuserid-get
      parameters:
      - in: path
        name: userid
      responses:
        200:
          description: OK
      tags:
      - User
      - Data
      - By
      - User
  /users/myself:
    patch:
      summary: Updates current user data
      description: Updates current user data.
      operationId: updateMyself
      x-api-path-slug: usersmyself-patch
      parameters:
      - in: body
        name: body
        description: Updated user info
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: If-Match
        description: User version
      responses:
        200:
          description: OK
      tags:
      - Current
      - User
      - Data
  /users/by-username/{username}:
    get:
      summary: Gets user data by username
      description: Gets user data by username.
      operationId: getUserByUsername
      x-api-path-slug: usersbyusernameusername-get
      parameters:
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - User
      - Data
      - By
      - Username
  /users/by-email/{email}:
    get:
      summary: Gets user data by email
      description: Gets user data by email.
      operationId: getUserByEmail
      x-api-path-slug: usersbyemailemail-get
      parameters:
      - in: path
        name: email
      responses:
        200:
          description: OK
      tags:
      - User
      - Data
      - By
      - Email
  /roles/{roleid}:
    get:
      summary: Gets role data.
      description: Gets role data..
      operationId: getRole
      x-api-path-slug: rolesroleid-get
      parameters:
      - in: path
        name: roleid
        description: Role identifier
      responses:
        200:
          description: OK
      tags:
      - Role
      - Data
  /projects/{projectid}:
    patch:
      summary: Updates project data
      description: Updates project data.
      operationId: updateProject
      x-api-path-slug: projectsprojectid-patch
      parameters:
      - in: body
        name: body
        description: Updated project info
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: If-Match
        description: Project version
      - in: path
        name: projectid
      responses:
        200:
          description: OK
      tags:
      - Project
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