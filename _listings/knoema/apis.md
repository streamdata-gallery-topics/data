---
name: Knoema
x-slug: knoema
description: Knoema is the free to use public and open data platform for users with
  interests in statistics and data analysis, visual storytelling and making infographics
  and data-driven presentations
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
x-kinRank: "8"
x-alexaRank: "38551"
tags: Data
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/knoema/apis.md
specificationVersion: "0.14"
apis:
- name: Knoema API List of datasets
  x-api-slug: knoema-api
  description: Returns the list of datasets
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0//meta/dataset
  tags: Datasets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/knoema/metadataset-get-openapi.md
- name: Knoema API Dataset details
  x-api-slug: knoema-api
  description: Lists out details of a particular dataset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0//meta/dataset/{dataset id}
  tags: Datasets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/knoema/metadatasetdataset-id-get-openapi.md
- name: Knoema API Dimension
  x-api-slug: knoema-api
  description: Lists out the given dataset's dimension details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0//meta/dataset/{datasetId}/dimension/{dimensionId}
  tags: Datasets,Dimensions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/knoema/metadatasetdatasetiddimensiondimensionid-get-openapi.md
- name: Knoema API Get timeseries list
  x-api-slug: knoema-api
  description: For the given dataset, this endpoint returns time series list for all
    the available frequencies with the combination of all the dimension members.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0//data/dataset/{dataset id}
  tags: Datasets,Time Series
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/knoema/datadatasetdataset-id-get-openapi.md
- name: Knoema API Get data
  x-api-slug: knoema-api
  description: This endpoint returns observation data for the given filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0//data/get
  tags: Datasets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/knoema/dataget-get-openapi.md
- name: Knoema API Search by keyword
  x-api-slug: knoema-api
  description: This namespace provides search details for data accessible by that
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0//search
  tags: Datasets,Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/knoema/search-get-openapi.md
- name: Knoema API
  x-api-slug: knoema-api
  description: Knoema is the free to use public and open data platform for users with
    interests in statistics and data analysis, visual storytelling and making infographics
    and data-driven presentations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/knoema-logo.jpg
  humanURL: https://knoema.com
  baseURL: http://knoema.com//api/1.0
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/knoema/openapi.md
x-common:
- type: x-authentication
  url: https://knoema.com/dev/apps/authentication
- type: x-blog
  url: http://blog.knoema.com/
- type: x-blog-rss
  url: http://blog.knoema.com/feeds/posts/default?alt=rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/knoema
- type: x-developer
  url: http://knoema.com/dev
- type: x-documentation
  url: https://knoema.com/dev/docs
- type: x-email
  url: jobs@knoema.com
- type: x-email
  url: veskin@knoema.com
- type: x-email
  url: jkasputys@knoema.com
- type: x-email
  url: vb@knoema.com
- type: x-email
  url: sales@knoema.com
- type: x-email
  url: info@knoema.com
- type: x-email
  url: support@knoema.com
- type: x-getting-started
  url: https://knoema.com/signup
- type: x-getting-started
  url: http://feedback.knoema.com/
- type: x-github
  url: https://github.com/knoema
- type: x-selfservice-registration
  url: https://knoema.com/sys/login?returnUrl=%2Fdev%2Fdocs%2Fmeta%2Fdatasets
- type: x-terms-of-service
  url: https://knoema.com/legal/termsofuse
- type: x-twitter
  url: https://twitter.com/knoema
- type: x-website
  url: https://knoema.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---