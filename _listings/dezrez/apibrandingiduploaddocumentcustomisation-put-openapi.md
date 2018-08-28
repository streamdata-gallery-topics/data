---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Upload the data to customise a Brand Document.
  version: 1.0.0
  description: Upload the data to customise a brand document..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/branding/{id}/uploaddocumentcustomisation:
    put:
      summary: Upload the data to customise a Brand Document.
      description: Upload the data to customise a brand document..
      operationId: Branding_UploadDocumentCustomisationByidBycustomisationSaveData
      x-api-path-slug: apibrandingiduploaddocumentcustomisation-put
      parameters:
      - in: body
        name: customisationSaveData
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: BrandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Data
      - To
      - Customise
      - Brand
      - Document
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