swagger: "2.0"
x-collection-name: SAP
x-complete: 1
info:
  title: SAP Translation Hub
  description: to-provide-users-of-software-in-a-global-market-with-texts-in-their-own-language-translations-are-required--sap-translation-hub-enables-you-to-draw-on-saps-translation-experience-across-multiple-products-and-languages-to-propose-translations-for-short-texts-
  contact:
    name: SAP Translation Hub team
    email: translationhub@sap.com
  version: 1.0.0
host: sandbox.api.sap.com
basePath: /translationhub/api/v1
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