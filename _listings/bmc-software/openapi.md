---
swagger: "2.0"
x-collection-name: BMC Software
x-complete: 1
info:
  title: BMC Software Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/datasets/*:
    get:
      summary: List dataset
      description: '*'
      operationId: list-dataset
      x-api-path-slug: v1datasets-get
      responses:
        200:
          description: OK
      tags:
      - Datasets
---