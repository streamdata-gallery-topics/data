---
swagger: "2.0"
x-collection-name: TigerText
x-complete: 1
info:
  title: Tiger Connect Metadata API
  description: the-metadata-system-for-tigerconnect-messaging-platform-
  termsOfService: http://www.tigertext.com/developer-terms-of-use
  contact:
    name: TigerText
    url: http://www.tigertext.com/supportform/
    email: info@tigertext.com
  version: v2
host: developer.tigertext.me
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /metadata/{group_token}/:
    delete:
      summary: Clears the metadata for a User or Group based on address encoding.
      description: Clears the metadata for a User or Group based on address encoding.
      operationId: deleteMetadata
      x-api-path-slug: metadatagroup-token-delete
      parameters:
      - in: path
        name: group_token
        description: The group token
      responses:
        200:
          description: OK
      tags:
      - Metadata
      - Group
      - Token
    get:
      summary: Get the metadata for a User or Group based on address encoding.
      description: Get the metadata for a User or Group based on address encoding.
      operationId: getMetadata
      x-api-path-slug: metadatagroup-token-get
      parameters:
      - in: path
        name: group_token
        description: The group token
      responses:
        200:
          description: OK
      tags:
      - Metadata
      - Group
      - Token
    post:
      summary: Adds metadata for a User or Group based on address encoding
      description: Adds metadata for a User or Group based on address encoding
      operationId: addMetadata
      x-api-path-slug: metadatagroup-token-post
      parameters:
      - in: body
        name: body
        description: The metadata in the body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: group_token
        description: The group token
      - in: query
        name: TT-X-Organization-Key
        description: The organization with which the entity is associated
      responses:
        200:
          description: OK
      tags:
      - Metadata
      - Group
      - Token
---