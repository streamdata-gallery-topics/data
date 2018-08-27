swagger: "2.0"
x-collection-name: Google Search Console
x-complete: 1
info:
  title: Google Search Console URL Testing Tools
  description: provides-tools-for-running-validation-tests-against-single-urls
  contact:
    name: Google
    url: https://google.com
  version: v1
host: searchconsole.googleapis.com
basePath: /
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