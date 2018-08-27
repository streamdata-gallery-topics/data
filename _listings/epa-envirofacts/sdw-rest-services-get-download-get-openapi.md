---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Safe Drinking
    Water Act Safe Drinking Water Act (SDWA) Download Data Service
  description: Based on the QID obtained from a get_systems query, return a comma
    sepated vaule (CSV) file of the water systems found.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sdw_rest_services.get_download:
    get:
      summary: Safe Drinking Water Act (SDWA) Download Data Service
      description: Based on the QID obtained from a get_systems query, return a comma
        sepated vaule (CSV) file of the water systems found.
      operationId: based-on-the-qid-obtained-from-a-get-systems-query-return-a-comma-sepated-vaule-csv-file-of-the-wate
      x-api-path-slug: sdw-rest-services-get-download-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Safe
      - Drinking
      - Water
      - Act
      - (SDWA)
      - Download
      - Data
      - Service
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