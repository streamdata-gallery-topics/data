---
swagger: "2.0"
info:
  title: Amazon Glacier API Set  Data  Retrieval  Policy
  version: 1.0.0
  description: "DescriptionThis operation sets and then enacts a data retrieval policy
    in the region specified in the PUT request. You can set one\n\t\t\tpolicy per
    region for an AWS account. The policy is enacted within a few minutes of a\n\t\t\tsuccessful
    PUT operation.  The set policy operation does not affect retrieval jobs that were
    in progress before the policy was\n\t\t\tenacted. For more information about data
    retrieval policies, see Amazon Glacier Data Retrieval Policies. Requests"
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{AccountId}/policies/data-retrieval:
    put:
      summary: Set  Data  Retrieval  Policy
      description: DescriptionThis operation sets and then enacts a data retrieval
        policy in the region specified in the PUT request
      operationId: Set Data Retrieval Policy (PUT policy)
      parameters:
      - in: query
        name: BytesPerHour
        description: The maximum number of bytes that can be retrieved in an hour
        type: string
      - in: query
        name: Rules
        description: The policy rule
        type: string
      - in: query
        name: Strategy
        description: The type of data retrieval policy to set
        type: string
      responses:
        200:
          description: OK
      tags:
      - data  retrieval  policy
definitions: []
x-collection-name: AWS Glacier
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