---
name: Google Biquery
x-slug: google-biquery
description: BigQuery is Googles fully managed, petabyte scale, low cost enterprise
  data warehouse for analytics. BigQuery is serverless. There is no infrastructure
  to manage and you dont need a database administrator, so you can focus on analyzing
  data to find meaningful insights using familiar SQL. BigQuery is a powerful Big
  Data analytics platform used by all types of organizations, from startups to Fortune
  500 companies.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Data
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/apis.md
specificationVersion: "0.14"
apis:
- name: Google BigQuery API Get Datasets
  x-api-slug: google-bigquery-api
  description: Lists all datasets in the specified project to which you have been
    granted the READER dataset role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2//projects/{projectId}/datasets
  tags: Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasets-get-openapi.md
- name: Google BigQuery API Create Dataset
  x-api-slug: google-bigquery-api
  description: Creates a new empty dataset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2//projects/{projectId}/datasets
  tags: Dataset
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasets-post-openapi.md
- name: Google BigQuery API Delete Dataset
  x-api-slug: google-bigquery-api
  description: Deletes the dataset specified by the datasetId value. Before you can
    delete a dataset, you must delete all its tables, either manually or by specifying
    deleteContents. Immediately after deletion, you can create another dataset with
    the same name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2//projects/{projectId}/datasets/{datasetId}
  tags: Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-delete-openapi.md
- name: Google BigQuery API Get Dataset
  x-api-slug: google-bigquery-api
  description: Returns the dataset specified by datasetID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2//projects/{projectId}/datasets/{datasetId}
  tags: Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-get-openapi.md
- name: Google BigQuery API Update Dataset
  x-api-slug: google-bigquery-api
  description: Updates information in an existing dataset. The update method replaces
    the entire dataset resource, whereas the patch method only replaces fields that
    are provided in the submitted dataset resource. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2//projects/{projectId}/datasets/{datasetId}
  tags: Dataset
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-patch-openapi.md
- name: Google BigQuery API Update Dataset
  x-api-slug: google-bigquery-api
  description: Updates information in an existing dataset. The update method replaces
    the entire dataset resource, whereas the patch method only replaces fields that
    are provided in the submitted dataset resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2//projects/{projectId}/datasets/{datasetId}
  tags: Dataset
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-put-openapi.md
- name: Google BigQuery API Get Table
  x-api-slug: google-bigquery-api
  description: Retrieves table data from a specified set of rows. Requires the READER
    dataset role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2//projects/{projectId}/datasets/{datasetId}/tables/{tableId}/data
  tags: Table Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetidtablestableiddata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetidtablestableiddata-get-openapi.md
- name: Google BigQuery API Insert Data
  x-api-slug: google-bigquery-api
  description: Streams data into BigQuery one record at a time without needing to
    run a load job. Requires the WRITER dataset role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2//projects/{projectId}/datasets/{datasetId}/tables/{tableId}/insertAll
  tags: Table Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/projectsprojectiddatasetsdatasetidtablestableidinsertall-post-openapi.md
- name: Google BigQuery API
  x-api-slug: google-bigquery-api
  description: BigQuery is Googles fully managed, petabyte scale, low cost enterprise
    data warehouse for analytics. BigQuery is serverless. There is no infrastructure
    to manage and you dont need a database administrator, so you can focus on analyzing
    data to find meaningful insights using familiar SQL. BigQuery is a powerful Big
    Data analytics platform used by all types of organizations, from startups to Fortune
    500 companies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-biquery/openapi.md
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
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---