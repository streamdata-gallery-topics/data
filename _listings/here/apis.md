---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Data
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Platform Data Extension API - Platform Static Data
  x-api-slug: static-json-get
  description: |-
    *Request enumerated content from a static data table*

    To request static data use the static.json endpoint and provide the name of the data table using the `content` parameter



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **content**  `text`
     \- The name of the static content table requested

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/static-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/static-json-get-openapi.md
- name: Platform Data Extension API - Available Map Data Layers
  x-api-slug: doclayers-json-get
  description: |-
    *Request which data layers can be accessed within a specified map region and release*

    To make a request for data layer availability information, use the `layers.json` endpoint, supplying the `release` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/doclayers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/doclayers-json-get-openapi.md
- name: Platform Data Extension API - Platform Data
  x-api-slug: tile-json-get
  description: |-
    *Request data from a specific data layer about a specified location*

    To request data  from a specified data layer, use the t`ile.json` endpoint, and include the `region`, `release` and `layer` parameters. The area covered is specified by the `level`, `tilex` and `tiley` parameters



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **layer**  `text`
     \- Thematic layer

    * **level**  `text`
     \- Specifies the size of the requested tile

    * **tilex**  `text`
     \- Specifies the tile number in West-East direction. This depends on the level.

    * **tiley**  `text`
     \- Specifies the tile number in South-North direction. This depends on the level.

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/tile-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/tile-json-get-openapi.md
- name: Platform Data Extension API - Map Data Availability and Freshness
  x-api-slug: docmaps-json-get
  description: |-
    *Request the release date and area covered by each available map region*

    To make a request for release date information, use the `maps.json` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/docmaps-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/docmaps-json-get-openapi.md
- name: Platform Data Extension API - Available Attributes within a Map Data Layer
  x-api-slug: doclayer-json-get
  description: |-
    *Request which attributes are available within a specified map data layer*

    To make a request for map data layer information, use the `layer``.json` endpoint, supplying the `release`, `layer` and `region` parameters.



    * **region**  `text`
     \- Map Coverage Region.    e.g. `APAC`, `NA`, `EU`

    * **release**  `text`
     \- Map release quarter    e.g. `2014Q4` or `LATEST`

    * **layer**  `text`
     \- Thematic layer

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/doclayer-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/doclayer-json-get-openapi.md
- name: Traffic API - Traffic Flow Availability Data
  x-api-slug: 6-0flowavailability-json-get
  description: |-
    *Flow availability requests allow you to see what traffic flow coverage exists in the current Traffic API.*

    T<i></i>he Server also supports an XML response.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/6-0flowavailability-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/6-0flowavailability-json-get-openapi.md
- name: Traffic API - Traffic Flow Availability Data
  x-api-slug: 6-0flowavailability-json-get
  description: |-
    *Flow availability requests allow you to see what traffic flow coverage exists in the current Traffic API.*

    T<i></i>he Server also supports an XML response.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/6-0flowavailability-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/here/6-0flowavailability-json-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---