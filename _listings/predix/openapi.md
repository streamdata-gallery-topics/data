swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
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
  /v1/collections/{collectionName}/assets/{assetId}:
    delete:
      summary: Delete an asset and its location data
      description: Delete the asset specified by the collection name. Any location
        data associated with the asset are also deleted.
      operationId: delete-the-asset-specified-by-the-collection-name-any-location-data-associated-with-the-asset-are-al
      x-api-path-slug: v1collectionscollectionnameassetsassetid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Asset
      - Its
      - Location
      - Data
  /v1/collections:
    get:
      summary: List all data collections for a customer
      description: |-
        Returns an array containing the names of all data collections for the
        specified customer.
      operationId: returns-an-array-containing-the-names-of-all-data-collections-for-thespecified-customer
      x-api-path-slug: v1collections-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Data
      - Collectionsa
      - Customer
  /v1/collections/{collectionName}:
    get:
      summary: Return all data for a collection
      description: |-
        Returns the full GeoJSON FeatureCollection uploaded for this collection.
        All GeoJSON Features will be as originally uploaded with the addition of
        a featureId attribute that uniquely identifies the feature across all
        your collections.
      operationId: returns-the-full-geojson-featurecollection-uploaded-for-this-collectionall-geojson-features-will-be-
      x-api-path-slug: v1collectionscollectionname-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Return
      - ""
      - Dataa
      - Collection
  /v1/maps/{mapId}/layers/{layerId}/style:
    get:
      summary: Retrieves style data for a layer
      description: |-
        Retrieve style data for the layer identified by the specified map and
        layer identifiers.
      operationId: retrieve-style-data-for-the-layer-identified-by-the-specified-map-andlayer-identifiers
      x-api-path-slug: v1mapsmapidlayerslayeridstyle-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieves
      - Style
      - Dataa
      - Layer
    put:
      summary: Update the style data for a layer
      description: |-
        Update the style data for the layer identified by the specified map and
        layer identifiers.
      operationId: update-the-style-data-for-the-layer-identified-by-the-specified-map-andlayer-identifiers
      x-api-path-slug: v1mapsmapidlayerslayeridstyle-put
      parameters:
      - in: body
        name: body
        description: Style data
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Style
      - Dataa
      - Layer