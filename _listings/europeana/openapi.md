---
swagger: "2.0"
x-collection-name: Europeana
x-complete: 1
info:
  title: Europeana
  description: this-swagger-api-console-provides-an-overview-of-an-interface-to-the-europeana-rest-api--you-can-build-and-test-anything-from-the-simplest-search-to-a-complex-query-using-facetlist-such-as-dates-geotags-and-permissions--for-more-help-and-information-head-to-our-comprehensive-a-hrefhttplabs-europeana-euapionline-documentationa-
  termsOfService: http://www.europeana.eu/portal/en/rights.html
  contact:
    name: http://labs.europeana.eu/api
  version: 1.0.0
host: www.europeana.eu
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dataset/{id}.json:
    get:
      summary: get information about a specific dataset
      description: Get information about a specific dataset.
      operationId: getDataset
      x-api-path-slug: datasetid-json-get
      parameters:
      - in: query
        name: callback
        description: callback
      - in: path
        name: id
        description: id
      - in: query
        name: wskey
        description: wskey
      responses:
        200:
          description: OK
      tags:
      - Dataset
      - Id
  /datasets.json:
    get:
      summary: get the list of Europeana datasets
      description: Get the list of europeana datasets.
      operationId: listDatasets
      x-api-path-slug: datasets-json-get
      parameters:
      - in: query
        name: callback
        description: callback
      - in: query
        name: countryCode
        description: countryCode
      - in: query
        name: edmDatasetName
        description: edmDatasetName
      - in: query
        name: offset
        description: offset
      - in: query
        name: pagesize
        description: pagesize
      - in: query
        name: status
        description: status
      - in: query
        name: wskey
        description: wskey
      responses:
        200:
          description: OK
      tags:
      - Datasets
  /provider/{id}/datasets.json:
    get:
      summary: get the list of datasets provided by a specific provider
      description: Get the list of datasets provided by a specific provider.
      operationId: listProviderDatasets
      x-api-path-slug: provideriddatasets-json-get
      parameters:
      - in: query
        name: callback
        description: callback
      - in: path
        name: id
        description: id
      - in: query
        name: wskey
        description: wskey
      responses:
        200:
          description: OK
      tags:
      - Providers
      - Datasets
---