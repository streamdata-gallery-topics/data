---
name: Google Content API for Shopping
x-slug: google-content-api-for-shopping
description: 'API allowing retailers to manage their product feed content programmatically.
  Providing item-level data quality information: See if an item was disapproved because
  a landing page URL isn&rsquo;t working on a mobile device or if unique product identifiers
  are inaccurate. Faster pricing and availability updates: Ensure customers have the
  latest price-points and know what&rsquo;s in-stock before they click through to
  your site. More integration options: The newer API supports a broader choice of
  programming languages and data formats.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Data
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/apis.md
specificationVersion: "0.14"
apis:
- name: Google Content API for Shopping API Data Feeds
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves data feed batches.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//datafeeds/batch
  tags: Data, Feeds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/datafeedsbatch-post-openapi.md
- name: Google Content API for Shopping API Data Feed Status
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves data feed batch status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//datafeedstatuses/batch
  tags: Data, Feed, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/datafeedstatusesbatch-post-openapi.md
- name: Google Content API for Shopping API Get Data Feeds
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the datafeeds in your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds
  tags: Data, Feeds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-get-openapi.md
- name: Google Content API for Shopping API Create Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Registers a datafeed with your Merchant Center account. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds
  tags: Data, Feed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeeds-post-openapi.md
- name: Google Content API for Shopping API Delete Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Deletes a datafeed from your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds/{datafeedId}
  tags: Data, Feed
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-delete-openapi.md
- name: Google Content API for Shopping API Get Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves a datafeed from your Merchant Center account. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds/{datafeedId}
  tags: Data, Feed
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-get-openapi.md
- name: Google Content API for Shopping API Update Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Updates a datafeed of your Merchant Center account. This method can
    only be called for non-multi-client accounts. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds/{datafeedId}
  tags: Data, Feed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-patch-openapi.md
- name: Google Content API for Shopping API Update Data Feed
  x-api-slug: google-content-api-for-shopping-api
  description: Updates a datafeed of your Merchant Center account. This method can
    only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeeds/{datafeedId}
  tags: Data, Feed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedsdatafeedid-put-openapi.md
- name: Google Content API for Shopping API Get Data Feed Status
  x-api-slug: google-content-api-for-shopping-api
  description: Lists the statuses of the datafeeds in your Merchant Center account.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeedstatuses
  tags: Data, Feed, Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatuses-get-openapi.md
- name: Google Content API for Shopping API Get Data Feed Status
  x-api-slug: google-content-api-for-shopping-api
  description: Retrieves the status of a datafeed from your Merchant Center account.
    This method can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2//{merchantId}/datafeedstatuses/{datafeedId}
  tags: Data, Feed, Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatusesdatafeedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/merchantiddatafeedstatusesdatafeedid-get-openapi.md
- name: Google Content API for Shopping API
  x-api-slug: google-content-api-for-shopping-api
  description: 'API allowing retailers to manage their product feed content programmatically.
    Providing item-level data quality information: See if an item was disapproved
    because a landing page URL isn&rsquo;t working on a mobile device or if unique
    product identifiers are inaccurate. Faster pricing and availability updates: Ensure
    customers have the latest price-points and know what&rsquo;s in-stock before they
    click through to your site. More integration options: The newer API supports a
    broader choice of programming languages and data formats.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-content-api-for-shopping/openapi.md
x-common:
- type: x-best-practices
  url: https://developers.google.com/shopping-content/v2/best-practices
- type: x-code
  url: https://developers.google.com/shopping-content/v2/libraries
- type: x-testing
  url: https://developers.google.com/shopping-content/v2/how-tos/testing
- type: x-website
  url: https://developers.google.com/shopping-content/v2/quickstart
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---