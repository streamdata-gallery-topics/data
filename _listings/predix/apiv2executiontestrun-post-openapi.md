---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Analytics Runtime Execute the orchestration with given bpmn and input
    data.
  version: 1.0.0
  description: To successfully execute the orchestration, the request must contain
    valid bpmn20.xml, input data for each step in the bpmn.
host: predix-acs.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/analytic/execution/async:
    post:
      summary: Execute the analytic asynchronously using input data.
      description: Execute the analytic asynchronously with the given input data payload.
      operationId: asynchronousExecution
      x-api-path-slug: apiv1analyticexecutionasync-post
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: body
        name: body
        description: request payload containing analytic input data
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      responses:
        2:
          description: Successful response
      tags:
      - Execute
      - Analytic
      - Asynchronously
      - Using
      - Input
      - Data
  /api/v1/analytics/customdata/read:
    post:
      summary: Retrieve analytic input data from custom datasource.
      description: Returns the analytic input data used during runtime execution.
      operationId: readCustomProviderData
      x-api-path-slug: apiv1analyticscustomdataread-post
      parameters:
      - in: body
        name: body
        description: Analytic Input Data Read request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Retrieve
      - Analytic
      - Input
      - Data
      - From
      - Custom
      - Datasource
  /api/v1/analytics/customdata/write:
    post:
      summary: Write analytic output data to custom datasource.
      description: Writes analytic output data generated during runtime execution.
      operationId: writeCustomProviderData
      x-api-path-slug: apiv1analyticscustomdatawrite-post
      parameters:
      - in: body
        name: body
        description: Analytic Output Data Write Request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: Successful response
      tags:
      - Write
      - Analytic
      - Output
      - Data
      - To
      - Custom
      - Datasource
  /api/v2/execution/testrun:
    post:
      summary: Execute the orchestration with given bpmn and input data.
      description: To successfully execute the orchestration, the request must contain
        valid bpmn20.xml, input data for each step in the bpmn.
      operationId: testRun
      x-api-path-slug: apiv2executiontestrun-post
      parameters:
      - in: formData
        name: bpmn
        description: BPMN file
      - in: formData
        name: input
        description: Input data file
      responses:
        200:
          description: Successful response
      tags:
      - Execute
      - Orchestration
      - Given
      - Bpmn
      - Input
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