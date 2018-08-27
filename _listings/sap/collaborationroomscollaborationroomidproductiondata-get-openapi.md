---
swagger: "2.0"
x-collection-name: SAP
x-complete: 0
info:
  title: SAP Manufacturing Network Partner APIs Retrieves the production data
  description: Retrieves the production data in a collaboration room, including the
    currency, all the production options, and the initial pricings provided by the
    supplier.
  version: 1.0.0
host: hostname
basePath: /dim/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /collaborationRooms/{collaborationRoomId}/productionData:
    get:
      summary: Retrieves the production data
      description: Retrieves the production data in a collaboration room, including
        the currency, all the production options, and the initial pricings provided
        by the supplier.
      operationId: retrieves-the-production-data-in-a-collaboration-room-including-the-currency-all-the-production-opti
      x-api-path-slug: collaborationroomscollaborationroomidproductiondata-get
      parameters:
      - in: path
        name: collaborationRoomId
        description: The ID of a collaboration room
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Production
      - Data
  /masterData:
    get:
      summary: Retrieves supplier profile master data
      description: |-
        Retrieves master data such as processes and materials.
        Narrow down the result by specifying the master data types.
      operationId: retrieves-master-data-such-as-processes-and-materialsnarrow-down-the-result-by-specifying-the-master
      x-api-path-slug: masterdata-get
      parameters:
      - in: query
        name: type
        description: 'A master data typeValid values: [certificates, currencies, materialRequirement,
          postProcesses, preferredLanguages, processMaterial, servicePortfolio]'
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Supplier
      - Profile
      - Master
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