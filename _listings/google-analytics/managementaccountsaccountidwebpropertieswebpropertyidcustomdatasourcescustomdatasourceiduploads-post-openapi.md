---
swagger: "2.0"
x-collection-name: Google Analytics
x-complete: 0
info:
  title: Google Analytics Upload Data
  description: Upload data for a custom data source.
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /analytics/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /management/accounts/{accountId}/webproperties/{webPropertyId}/customDataSources/{customDataSourceId}/deleteUploadData:
    post:
      summary: Delete Data
      description: Delete data associated with a previous upload.
      operationId: analytics.management.uploads.deleteUploadData
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustomdatasourcescustomdatasourceiddeleteuploaddata-post
      parameters:
      - in: path
        name: accountId
        description: Account Id for the uploads to be deleted
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customDataSourceId
        description: Custom data source Id for the uploads to be deleted
      - in: path
        name: webPropertyId
        description: Web property Id for the uploads to be deleted
      responses:
        200:
          description: OK
      tags:
      - Data
  /management/accounts/{accountId}/webproperties/{webPropertyId}/customDataSources/{customDataSourceId}/uploads:
    post:
      summary: Upload Data
      description: Upload data for a custom data source.
      operationId: analytics.management.uploads.uploadData
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustomdatasourcescustomdatasourceiduploads-post
      parameters:
      - in: path
        name: accountId
        description: Account Id associated with the upload
      - in: path
        name: customDataSourceId
        description: Custom data source Id to which the data being uploaded belongs
      - in: path
        name: webPropertyId
        description: Web property UA-string associated with the upload
      responses:
        200:
          description: OK
      tags:
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