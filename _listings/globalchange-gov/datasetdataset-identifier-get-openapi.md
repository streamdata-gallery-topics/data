---
swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 0
info:
  title: Global Change Information System API Get a representation of a dataset.
  description: Get JSON which represents the structure of a dataset.
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dataset:
    get:
      summary: List datasets.
      description: List the datasets, 20 per page.
      operationId: list-the-datasets-20-per-page
      x-api-path-slug: dataset-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the datasets
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Datasets
  /dataset/lookup/{doi}:
    get:
      summary: Look up a dataset by DOI.
      description: Given a DOI, return a redirect to the GCIS dataset.
      operationId: given-a-doi-return-a-redirect-to-the-gcis-dataset
      x-api-path-slug: datasetlookupdoi-get
      parameters:
      - in: path
        name: doi
        description: doi description
      responses:
        200:
          description: OK
      tags:
      - Look
      - Up
      - Dataset
      - By
      - DOI
  /dataset/{dataset_identifier}:
    get:
      summary: Get a representation of a dataset.
      description: Get JSON which represents the structure of a dataset.
      operationId: get-json-which-represents-the-structure-of-a-dataset
      x-api-path-slug: datasetdataset-identifier-get
      parameters:
      - in: path
        name: dataset_identifier
        description: dataset_identifier description
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Dataset
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