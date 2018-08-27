swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
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
  /users/{user_id}/custom_data(/*scope):
    delete:
      summary: Delete custom data
      description: Delete custom data.
      operationId: delete-custom-data
      x-api-path-slug: usersuser-idcustom-datascope-delete
      parameters:
      - in: query
        name: ns
        description: The namespace from which to delete the data
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Custom
      - Data(
      - '*scope)'
    get:
      summary: Load custom data
      description: Load custom data.
      operationId: load-custom-data
      x-api-path-slug: usersuser-idcustom-datascope-get
      parameters:
      - in: query
        name: ns
        description: The namespace from which to retrieve the data
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Custom
      - Data(
      - '*scope)'
    put:
      summary: Store custom data
      description: Store custom data.
      operationId: store-custom-data
      x-api-path-slug: usersuser-idcustom-datascope-put
      parameters:
      - in: query
        name: data
        description: The data you want to store for the user, at the specified scope
      - in: query
        name: ns
        description: The namespace under which to store the data
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Custom
      - Data(
      - '*scope)'