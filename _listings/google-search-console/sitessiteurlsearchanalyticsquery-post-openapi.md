---
swagger: "2.0"
x-collection-name: Google Search Console
x-complete: 0
info:
  title: Google Search Console API Query Data
  description: |-
    Query your data with filters and parameters that you define. Returns zero or more rows grouped by the row keys that you define. You must define a date range of one or more days.

    When date is one of the group by values, any days without data are omitted from the result list. If you need to know which days have data, issue a broad date range query grouped by date for any metric, and see which day rows are returned.
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /webmasters/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sites/{siteUrl}/searchAnalytics/query:
    post:
      summary: Query Data
      description: |-
        Query your data with filters and parameters that you define. Returns zero or more rows grouped by the row keys that you define. You must define a date range of one or more days.

        When date is one of the group by values, any days without data are omitted from the result list. If you need to know which days have data, issue a broad date range query grouped by date for any metric, and see which day rows are returned.
      operationId: webmasters.searchanalytics.query
      x-api-path-slug: sitessiteurlsearchanalyticsquery-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: siteUrl
        description: The sites URL, including protocol
      responses:
        200:
          description: OK
      tags:
      - Data
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