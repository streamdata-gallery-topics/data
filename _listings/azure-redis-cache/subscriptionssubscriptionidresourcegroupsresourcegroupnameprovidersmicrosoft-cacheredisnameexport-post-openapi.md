---
swagger: "2.0"
x-collection-name: Azure Redis Cache
x-complete: 0
info:
  title: Azure Redis Cache API Redis Export Data
  description: Export data from the redis cache to blobs in a container.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/import:
    post:
      summary: Redis Import Data
      description: Import data into Redis cache.
      operationId: Redis_ImportData
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnameimport-post
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters for Redis import operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis Import Data
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cache/Redis/{name}/export:
    post:
      summary: Redis Export Data
      description: Export data from the redis cache to blobs in a container.
      operationId: Redis_ExportData
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cacheredisnameexport-post
      parameters:
      - in: path
        name: name
        description: The name of the Redis cache
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters for Redis export operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Redis Export Data
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