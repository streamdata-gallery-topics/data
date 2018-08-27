swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dataset/data/{dataSetId}:
    get:
      summary: DataSet Data
      description: Get Data for DataSet
      operationId: dataSetData
      x-api-path-slug: datasetdatadatasetid-get
      parameters:
      - in: path
        name: dataSetId
        description: The DataSet ID
      responses:
        200:
          description: OK
      tags:
      - DataSet
      - Data
  /user/permissions/{entity}/{objectId}:
    get:
      summary: Permission Data
      description: Permission data for the Entity and Object Provided.
      operationId: userPermissionsSearch
      x-api-path-slug: userpermissionsentityobjectid-get
      parameters:
      - in: path
        name: entity
        description: The Entity
      - in: path
        name: objectId
        description: The ID of the Object to return permissions for
      responses:
        200:
          description: OK
      tags:
      - Permission
      - Data