---
name: Google Genomics
description: Google Genomics helps the life science community organize the worldrsquo;s
  genomic information and make it accessible and useful. Big genomic data is here
  today, with petabytes rapidly growing toward exabytes. Through our extensions to
  Google Cloud Platform, you can apply the same technologies that power Google Search
  and Maps to securely store, process, explore, and share large, complex datasets.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/power-your-science.png
x-kinRank: "9"
x-alexaRank: ""
tags:
- Stack Network
- Science
- Google APIs
- Genome
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-genomics/apis.yaml
specificationVersion: "0.14"
apis:
- name: Google Genomics API
  description: Google Genomics helps the life science community organize the worldrsquo;s
    genomic information and make it accessible and useful
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/power-your-science.png
  humanURL: ""
  baseURL: ://genomics.googleapis.com//
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-genomics/v1-datasets-datasetid-undelete-post.md
- name: Google Genomics API Delete Dataset
  description: |-
    Deletes a dataset and all of its contents (all read group sets,
    reference sets, variant sets, call sets, annotation sets, etc.)
    This is reversible (up to one week after the deletion) via
    the
    datasets.undelete
    operation.

    For the definitions of datasets and other genomics resources, see
    [Fundamentals of Google
    Genomics](https://cloud.google.com/genomics/fundamentals-of-google-genomics)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/power-your-science.png
  humanURL: https://cloud.google.com/genomics/
  baseURL: http:://genomics.googleapis.com//
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-genomics/v1-datasets-datasetid-delete.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-genomics/v1-datasets-datasetid-delete-postman.md
x-common:
- type: x-documentation
  url: https://cloud.google.com/genomics/overview
- type: x-forum
  url: https://groups.google.com/forum/#!forum/google-genomics-discuss/join
- type: x-pricing
  url: https://cloud.google.com/genomics/pricing
- type: x-rate-limits
  url: https://cloud.google.com/genomics/quotas
- type: x-support
  url: https://cloud.google.com/genomics/support
- type: x-website
  url: https://cloud.google.com/genomics/
- type: x-documentation
  url: https://cloud.google.com/genomics/overview
- type: x-forum
  url: https://groups.google.com/forum/#!forum/google-genomics-discuss/join
- type: x-pricing
  url: https://cloud.google.com/genomics/pricing
- type: x-rate-limits
  url: https://cloud.google.com/genomics/quotas
- type: x-support
  url: https://cloud.google.com/genomics/support
- type: x-website
  url: https://cloud.google.com/genomics/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---