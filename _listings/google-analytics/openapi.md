---
swagger: "2.0"
x-collection-name: Google Analytics
x-complete: 1
info:
  title: Google Analytics
  description: views-and-manages-your-google-analytics-data-
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
---