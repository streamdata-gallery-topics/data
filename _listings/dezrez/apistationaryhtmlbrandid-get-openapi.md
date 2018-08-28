---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: "Dezrez Does a simple merge of the selected envelopeTemplatePack using the
    data supplied\r\nwill only use certain merge functions, and the correspondence
    can only contain one envelope and the envelope can only contain one document."
  version: 1.0.0
  description: "Does a simple merge of the selected envelopetemplatepack using the
    data supplied\r\nwill only use certain merge functions, and the correspondence
    can only contain one envelope and the envelope can only contain one document.."
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
  /api/branding/uploadsmstemplate:
    post:
      summary: Upload the data to create a SMS Document Template for a Brand.
      description: Upload the data to create a sms document template for a brand..
      operationId: Branding_UploadSMSTemplateBybrandTemplateSaveDataContract
      x-api-path-slug: apibrandinguploadsmstemplate-post
      parameters:
      - in: body
        name: brandTemplateSaveDataContract
        schema:
          $ref: '#/definitions/holder'
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
      - Create
      - SMS
      - Document
      - Templatea
      - Brand
  /api/branding/uploademailtemplate:
    post:
      summary: Upload the data to create a Email Document Template for a Brand.
      description: Upload the data to create a email document template for a brand..
      operationId: Branding_UploadEmailTemplateBybrandTemplateSaveDataContract
      x-api-path-slug: apibrandinguploademailtemplate-post
      parameters:
      - in: body
        name: brandTemplateSaveDataContract
        schema:
          $ref: '#/definitions/holder'
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
      - Create
      - Email
      - Document
      - Templatea
      - Brand
  /api/coreplatformstate/reportMigration:
    post:
      summary: Reports that a data migration has been shedueled.
      description: Reports that a data migration has been shedueled..
      operationId: CorePlatformState_ReportMigrationStateBymigrationState
      x-api-path-slug: apicoreplatformstatereportmigration-post
      parameters:
      - in: body
        name: migrationState
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Reports
      - That
      - Data
      - Migration
      - Has
      - Been
      - Shedueled
  /api/coreplatformstate/reportMigration/{migrationId}:
    post:
      summary: Reports that a data migration has been shedueled - used by workflow
      description: Reports that a data migration has been shedueled - used by workflow.
      operationId: CorePlatformState_ReportMigrationStateBymigrationId
      x-api-path-slug: apicoreplatformstatereportmigrationmigrationid-post
      parameters:
      - in: path
        name: migrationId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Reports
      - That
      - Data
      - Migration
      - Has
      - Been
      - Shedueled
      - '-'
      - Used
      - By
      - Workflow
  /api/documentgeneration/metadata/{major}/{minor}/{build}/{revision}:
    get:
      summary: Returns the data contract to configure the word plugin for creating
        templates
      description: Returns the data contract to configure the word plugin for creating
        templates.
      operationId: DocumentGeneration_GetLetterEditorDataContractBymajorByminorBybuildByrevision
      x-api-path-slug: apidocumentgenerationmetadatamajorminorbuildrevision-get
      parameters:
      - in: path
        name: build
      - in: path
        name: major
      - in: path
        name: minor
      - in: path
        name: revision
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Data
      - Contract
      - To
      - Configure
      - Word
      - Plugincreating
      - Templates
  /api/stationary/html/{brandId}:
    get:
      summary: "Does a simple merge of the selected envelopeTemplatePack using the
        data supplied\r\nwill only use certain merge functions, and the correspondence
        can only contain one envelope and the envelope can only contain one document."
      description: "Does a simple merge of the selected envelopetemplatepack using
        the data supplied\r\nwill only use certain merge functions, and the correspondence
        can only contain one envelope and the envelope can only contain one document.."
      operationId: Stationary_HtmlStationaryBybrandId
      x-api-path-slug: apistationaryhtmlbrandid-get
      parameters:
      - in: path
        name: brandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Does
      - Simple
      - Merge
      - Of
      - Selected
      - EnvelopeTemplatePack
      - Using
      - Data
      - "Supplied\r\nWill"
      - Only
      - Use
      - Certain
      - Merge
      - Functions
      - ""
      - Correspondence
      - Can
      - Only
      - Contain
      - Envelope
      - Envelope
      - Can
      - Only
      - Contain
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