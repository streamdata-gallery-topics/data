---
name: Google Analytics
x-slug: google-analytics
description: Google Analytics gives you the digital analytics tools you need to analyze
  data from all touchpoints in one place, for a deeper understanding of the customer
  experience. You can then share the insights that matter with your whole organization.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Data
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/apis.md
specificationVersion: "0.14"
apis:
- name: Google Analytics Return Analytics Data
  x-api-slug: google-analytics
  description: Returns Analytics data for a view (profile).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//data/ga
  tags: Analytic Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/dataga-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/dataga-get-openapi.md
- name: Google Analytics Returns Analytics Multi-Channel Funnels Data
  x-api-slug: google-analytics
  description: Returns Analytics Multi-Channel Funnels data for a view (profile).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//data/mcf
  tags: Analytic Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/datamcf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/datamcf-get-openapi.md
- name: Google Analytics Return Real Time Data
  x-api-slug: google-analytics
  description: Returns real time data for a view (profile).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//data/realtime
  tags: Real Time Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/datarealtime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/datarealtime-get-openapi.md
- name: Google Analytics Get Custom Data
  x-api-slug: google-analytics
  description: List custom data sources to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customDataSources
  tags: Custom Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdatasources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdatasources-get-openapi.md
- name: Google Analytics Delete Data
  x-api-slug: google-analytics
  description: Delete data associated with a previous upload.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customDataSources/{customDataSourceId}/deleteUploadData
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdatasourcescustomdatasourceiddeleteuploaddata-post-openapi.md
- name: Google Analytics Upload Data
  x-api-slug: google-analytics
  description: Upload data for a custom data source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customDataSources/{customDataSourceId}/uploads
  tags: Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdatasourcescustomdatasourceiduploads-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdatasourcescustomdatasourceiduploads-post-openapi.md
- name: Google Analytics
  x-api-slug: google-analytics
  description: Google Analytics gives you the digital analytics tools you need to
    analyze data from all touchpoints in one place, for a deeper understanding of
    the customer experience. You can then share the insights that matter with your
    whole organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-analytics/openapi.md
x-common:
- type: x-blog
  url: https://analytics.googleblog.com/
- type: x-blog-rss
  url: https://analytics.googleblog.com/feeds/posts/default?alt=rss
- type: x-developer
  url: https://developers.google.com/analytics/
- type: x-github
  url: https://github.com/googleanalytics/
- type: x-google-plus
  url: https://plus.google.com/+GoogleAnalytics
- type: x-partners
  url: https://developers.google.com/analytics/program/
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/google-analytics
- type: x-support
  url: https://developers.google.com/analytics/help/
- type: x-twitter
  url: https://twitter.com/googleanalytics
- type: x-videos
  url: https://www.youtube.com/user/googleanalytics
- type: x-website
  url: https://www.google.com/analytics/#?modal_active=none
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---