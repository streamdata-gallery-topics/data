---
swagger: "2.0"
x-collection-name: Botify
x-complete: 1
info:
  title: Botify
  description: botify-saas-api
  version: 1.0.0
host: api.botify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /analyses/{username}/{project_slug}/{analysis_slug}/urls/datamodel:
    get:
      summary: Get Analyses Username Project Slug Analysis Slug Urls Datamodel
      description: Get analyses username project slug analysis slug urls datamodel.
      operationId: getAnalysesUsernameProjectSlugAnalysisSlugUrlsDatamodel
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurlsdatamodel-get
      parameters:
      - in: query
        name: area
        description: Analysis context
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
      - Datamodel
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Urls Datamodel
      description: Parameters analyses username project slug analysis slug urls datamodel.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugUrlsDatamodel
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurlsdatamodel-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
      - Datamodel
---