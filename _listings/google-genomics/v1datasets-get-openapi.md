---
swagger: "2.0"
x-collection-name: Google Genomics
x-complete: 0
info:
  title: Google Genomics API Get Datasets
  description: |-
    Lists datasets within a project.

    For the definitions of datasets and other genomics resources, see
    [Fundamentals of Google
    Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)
  contact:
    name: Google
    url: https://google.com
  version: v1
host: genomics.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/datasets:
    get:
      summary: Get Datasets
      description: |-
        Lists datasets within a project.

        For the definitions of datasets and other genomics resources, see
        [Fundamentals of Google
        Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)
      operationId: genomics.datasets.list
      x-api-path-slug: v1datasets-get
      parameters:
      - in: query
        name: pageSize
        description: The maximum number of results to return in a single page
      - in: query
        name: pageToken
        description: The continuation token, which is used to page through large result
          sets
      - in: query
        name: projectId
        description: Required
      responses:
        200:
          description: OK
      tags:
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