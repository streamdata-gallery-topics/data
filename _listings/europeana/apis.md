---
name: Europeana
x-slug: europeana
description: Explore 51,990,182 artworks, artefacts, books, videos and sounds from
  more than 3,500 museums, galleries, libraries and archives across Europe.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
x-kinRank: "9"
x-alexaRank: "68066"
tags: Data
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/europeana/apis.md
specificationVersion: "0.14"
apis:
- name: Europeana get information about a specific dataset
  x-api-slug: europeana
  description: Get information about a specific dataset.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///dataset/{id}.json
  tags: Dataset,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/europeana/datasetid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/europeana/datasetid-json-get-openapi.md
- name: Europeana get the list of Europeana datasets
  x-api-slug: europeana
  description: Get the list of europeana datasets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///datasets.json
  tags: Datasets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/europeana/datasets-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/europeana/datasets-json-get-openapi.md
- name: Europeana get the list of datasets provided by a specific provider
  x-api-slug: europeana
  description: Get the list of datasets provided by a specific provider.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2///provider/{id}/datasets.json
  tags: Providers,Datasets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/europeana/provideriddatasets-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/europeana/provideriddatasets-json-get-openapi.md
- name: Europeana
  x-api-slug: europeana
  description: Explore 51,990,182 artworks, artefacts, books, videos and sounds from
    more than 3,500 museums, galleries, libraries and archives across Europe.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/777-europeana.jpg
  humanURL: http://europeana.eu/portal/
  baseURL: https://www.europeana.eu/v2/
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/europeana/openapi.md
x-common:
- type: x-base
  url: http://www.europeana.eu/api/
- type: x-blog
  url: http://blog.europeana.eu/
- type: x-blog-rss
  url: http://blog.europeana.eu/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/europeana
- type: x-developer
  url: http://europeana.eu/portal/api-introduction.html
- type: x-github
  url: https://github.com/europeana
- type: x-twitter
  url: https://twitter.com/EuropeanaEU
- type: x-website
  url: http://europeana.eu/portal/
- type: x-website
  url: http://europeana.eu
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---