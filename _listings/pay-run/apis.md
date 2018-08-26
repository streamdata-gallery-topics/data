---
name: Pay Run
x-slug: pay-run
description: PayRun.io is a RESTful payroll and auto enrolment API built by developers
  for developers. It is a 100% compliant solution hosted in our own private cloud,
  providing realtime payroll calculations and regulatory reporting to HMRC.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/payrun-logo.jpeg
x-kinRank: "7"
x-alexaRank: "0"
tags: Data
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/pay-run/apis.md
specificationVersion: "0.14"
apis:
- name: Pay Run.IO Get a list of all available data object tempaltes
  x-api-slug: pay-run-io
  description: Returns a collection of links to all the available data object templates
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/payrun-logo.jpeg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates
  tags: List,Of,,Available,Data,Object,Tempaltes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/pay-run/templates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/pay-run/templates-get-openapi.md
- name: Pay Run.IO
  x-api-slug: pay-run-io
  description: PayRun.io is a RESTful payroll and auto enrolment API built by developers
    for developers. It is a 100% compliant solution hosted in our own private cloud,
    providing realtime payroll calculations and regulatory reporting to HMRC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/payrun-logo.jpeg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/pay-run/openapi.md
x-common:
- type: x-website
  url: http://www.payrun.io
- type: x-documentation
  url: https://developer.payrun.io/docs/home/index.html
- type: x-twitter
  url: https://twitter.com/PayRun_io
- type: x-website
  url: http://api.test.payrun.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---