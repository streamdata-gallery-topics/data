---
swagger: "2.0"
x-collection-name: OpenDataSoft
x-complete: 0
info:
  title: OpenDataSoft Get Source Datasets Dataset
  description: |-
    List of available endpoints for the specified dataset, with metadata and endpoints.

    Will provide links for:
    * the attachments endpoint
    * the files endpoint
    * the records endpoint
    * the catalog endpoint
  version: 2.1.0
host: public.opendatasoft.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{source}/datasets:
    get:
      summary: Get Source Datasets
      description: |-
        List of available datasets, each with their endpoints, paginated.

        Links provided:
        * previous page
        * next page
        * last page
        * first page
      operationId: getDatasets
      x-api-path-slug: sourcedatasets-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
  /{source}/datasets/{dataset_id}:
    get:
      summary: Get Source Datasets Dataset
      description: |-
        List of available endpoints for the specified dataset, with metadata and endpoints.

        Will provide links for:
        * the attachments endpoint
        * the files endpoint
        * the records endpoint
        * the catalog endpoint
      operationId: getDataset
      x-api-path-slug: sourcedatasetsdataset-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
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