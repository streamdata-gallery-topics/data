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
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-search-console/apis.md
specificationVersion: "0.14"
apis:
- name: Google Search Console API Query Data
  x-api-slug: google-search-console-api
  description: |-
    Query your data with filters and parameters that you define. Returns zero or more rows grouped by the row keys that you define. You must define a date range of one or more days.

    When date is one of the group by values, any days without data are omitted from the result list. If you need to know which days have data, issue a broad date range query grouped by date for any metric, and see which day rows are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3//sites/{siteUrl}/searchAnalytics/query
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-search-console/sitessiteurlsearchanalyticsquery-post-openapi.md
- name: Google Search Console API
  x-api-slug: google-search-console-api
  description: Query search analytics, list your verified sites, manage your sitemaps,
    and view crawl errors for your site.The Search Console API provides programmatic
    access to most of the functionality ofGoogle Search Console. You can use the API
    to view, add, or remove properties and sitemaps, and run advanced queries for
    Google Search results data for the properties that you manage in Search Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-search-console/openapi.md
x-common:
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