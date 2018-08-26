---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Intelligent Mapping Return all data for a collection
  description: |-
    Returns the full GeoJSON FeatureCollection uploaded for this collection.
    All GeoJSON Features will be as originally uploaded with the addition of
    a featureId attribute that uniquely identifies the feature across all
    your collections.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
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