---
swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 1
info:
  title: My Space
  description: create-apps-and-games-within-the-myspace-platform--monetize-through-advertising-and-virtual-goods-
  version: 1.0.0
host: api.myspace.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1.0/appdata/{personId}/{selector}/{appId}:
    delete:
      summary: Delete Appdata Personid Selector Appid
      description: Deletes a specified user's application data.
      operationId: 1.0.appdata.personId.selector.appId.delete
      x-api-path-slug: 1-0appdatapersonidselectorappid-delete
      parameters:
      - in: path
        name: appId
        description: The applications ID associated with the OAuth ConsumerKey/ConsumerSecret
          pair
      - in: query
        name: fields
        description: The fields correspond to keys in the application data
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      responses:
        200:
          description: OK
      tags:
      - Appdata
      - People
      - Selector
      - AppId
    post:
      summary: Post Appdata Personid Selector Appid
      description: Adds or updates a specified user's application data.
      operationId: 1.0.appdata.personId.selector.appId.post
      x-api-path-slug: 1-0appdatapersonidselectorappid-post
      parameters:
      - in: path
        name: appId
        description: The applications ID associated with the OAuth ConsumerKey/ConsumerSecret
          pair
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: fields
        description: The fields correspond to keys in the application data
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      responses:
        200:
          description: OK
      tags:
      - Appdata
      - People
      - Selector
      - AppId
    get:
      summary: Get Appdata Personid Selector Appid
      description: Retrieves all application data for a specified user.
      operationId: 1.0.appdata.personId.selector.appId.get
      x-api-path-slug: 1-0appdatapersonidselectorappid-get
      parameters:
      - in: path
        name: appId
        description: The applications ID associated with the OAuth ConsumerKey/ConsumerSecret
          pair
      - in: query
        name: fields
        description: The fields correspond to keys in the application data
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      responses:
        200:
          description: OK
      tags:
      - Appdata
      - People
      - Selector
      - AppId
---