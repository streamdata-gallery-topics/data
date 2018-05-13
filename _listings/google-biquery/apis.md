---
name: Google Biquery
description: BigQuery is Googles fully managed, petabyte scale, low cost enterprise
  data warehouse for analytics. BigQuery is serverless. There is no infrastructure
  to manage and you dont need a database administrator, so you can focus on analyzing
  data to find meaningful insights using familiar SQL. BigQuery is a powerful Big
  Data analytics platform used by all types of organizations, from startups to Fortune
  500 companies.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
x-kinRank: "9"
x-alexaRank: ""
tags:
- Stack Network
- Google APIs
- Database
- Data
- Cloud
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/apis.yaml
specificationVersion: "0.14"
apis:
- name: Google BigQuery API
  description: BigQuery is Googles fully managed, petabyte scale, low cost enterprise
    data warehouse for analytics
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: ""
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projects-projectid-datasets-datasetid-tables-tableid-insertall-post.md
- name: Google BigQuery API Delete Dataset
  description: Deletes the dataset specified by the datasetId value. Before you can
    delete a dataset, you must delete all its tables, either manually or by specifying
    deleteContents. Immediately after deletion, you can create another dataset with
    the same name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: http:://www.googleapis.com//bigquery/v2
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projects-projectid-datasets-datasetid-delete.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projects-projectid-datasets-datasetid-delete-postman.md
x-common:
- type: x-code
  url: https://cloud.google.com/bigquery/docs/reference/libraries
- type: x-documentation
  url: https://cloud.google.com/bigquery/docs/
- type: x-getting-started
  url: https://cloud.google.com/bigquery/docs/quickstarts
- type: x-how-to-guides
  url: https://cloud.google.com/bigquery/docs/how-to
- type: x-partners
  url: https://cloud.google.com/bigquery/partners/
- type: x-pricing
  url: https://cloud.google.com/bigquery/pricing
- type: x-quotas
  url: https://cloud.google.com/bigquery/quota-policy
- type: x-service-level-agreement
  url: https://cloud.google.com/bigquery/sla
- type: x-support
  url: https://cloud.google.com/bigquery/support
- type: x-tutorials
  url: https://cloud.google.com/bigquery/docs/tutorials
- type: x-website
  url: https://cloud.google.com/bigquery/
- type: x-code
  url: https://cloud.google.com/bigquery/docs/reference/libraries
- type: x-documentation
  url: https://cloud.google.com/bigquery/docs/
- type: x-getting-started
  url: https://cloud.google.com/bigquery/docs/quickstarts
- type: x-how-to-guides
  url: https://cloud.google.com/bigquery/docs/how-to
- type: x-partners
  url: https://cloud.google.com/bigquery/partners/
- type: x-pricing
  url: https://cloud.google.com/bigquery/pricing
- type: x-quotas
  url: https://cloud.google.com/bigquery/quota-policy
- type: x-service-level-agreement
  url: https://cloud.google.com/bigquery/sla
- type: x-support
  url: https://cloud.google.com/bigquery/support
- type: x-tutorials
  url: https://cloud.google.com/bigquery/docs/tutorials
- type: x-website
  url: https://cloud.google.com/bigquery/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---