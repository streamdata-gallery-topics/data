---
swagger: "2.0"
x-collection-name: IBM Financial Crimes Insight for Insurance
x-complete: 0
info:
  title: IBM Financial Crimes Insight for Insurance API Retrieve group data from the
    database, for the specific group id
  description: This method is used to retrieve specific group data from the database
  version: 1.0.0
host: fcihost.ibm.com:9443
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ibm/fci/platform/fact/account:
    put:
      summary: Insert account data into the database
      description: This method is used to insert account data into the database.  The
        XML schema is defined in the ACCOUNT.XSD file.
      operationId: putAccount
      x-api-path-slug: ibmfciplatformfactaccount-put
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Account
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/account/{id}:
    get:
      summary: Retrieve account data from the database, for the id
      description: This method is used to retrieve account data from the database
      operationId: getAccount
      x-api-path-slug: ibmfciplatformfactaccountid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Account
      - Data
      - From
      - Database
      - The
      - Id
  /ibm/fci/platform/fact/event:
    put:
      summary: Insert event data into the database
      description: This method is used to insert event data into the database.  The
        XML schema is defined in the EVENT.XSD file.
      operationId: putEvent
      x-api-path-slug: ibmfciplatformfactevent-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Event
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/event/{id}:
    get:
      summary: Retrieve event data from the database, for the id
      description: This method is used to retrieve event data from the database
      operationId: getEvent
      x-api-path-slug: ibmfciplatformfacteventid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Event
      - Data
      - From
      - Database
      - The
      - Id
  /ibm/fci/platform/fact/group:
    put:
      summary: Insert group data into the database
      description: This method is used to insert group data into the database.  The
        XML schema is defined in the GROUP.XSD file.
      operationId: putGroup
      x-api-path-slug: ibmfciplatformfactgroup-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Group
      - Data
      - Into
      - Database
  /ibm/fci/platform/fact/group/{id}:
    get:
      summary: Retrieve group data from the database, for the specific group id
      description: This method is used to retrieve specific group data from the database
      operationId: getGroup
      x-api-path-slug: ibmfciplatformfactgroupid-get
      parameters:
      - in: header
        name: IBM-FCI-Role
        description: Userid / password for user with appropriate role
      - in: header
        name: IBM-FCI-Token
        description: Security token obtained for execution
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Group
      - Data
      - From
      - Database
      - The
      - Specific
      - Group
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