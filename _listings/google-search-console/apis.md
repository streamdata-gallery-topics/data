---
name: Google Search Console
x-slug: google-search-console
description: Search Console is a free service that enables you to monitor your sites
  performance in Google Search, to ensure that Google can crawl your site or app correctly,
  and to test the validity and performance of a given page. Search Console provides
  programmatic access to the service through the APIs documented here.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
x-kinRank: "9"
x-alexaRank: "0"
tags: Data
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-search-console/apis.md
specificationVersion: "0.14"
apis:
- name: Search Console - Query Data
  x-api-slug: sitessiteurlsearchanalyticsquery-post
  description: |-
    Query your data with filters and parameters that you define. Returns zero or more rows grouped by the row keys that you define. You must define a date range of one or more days.

    When date is one of the group by values, any days without data are omitted from the result list. If you need to know which days have data, issue a broad date range query grouped by date for any metric, and see which day rows are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-search-console/sitessiteurlsearchanalyticsquery-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.safe.browsing.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.search.console.stack.network
- type: x-blog
  url: https://support.google.com/webmasters/go/blog
- type: x-blog-rss
  url: https://webmasters.googleblog.com/feeds/posts/default?alt=rss
- type: x-forum
  url: https://productforums.google.com/forum/#!forum/webmasters
- type: x-website
  url: https://developers.google.com/webmaster-tools/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---