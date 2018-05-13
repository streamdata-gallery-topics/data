---
name: Google Fit
description: Google Fit is an open ecosystem that allows developers to upload fitness
  data to a central repository where users can access their data from different devices
  and apps in one location. Fitness apps can store data from any wearable or sensor.
  Fitness apps can access data created by any app. Users fitness data is persisted
  when they upgrade their fitness devices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
x-kinRank: "9"
x-alexaRank: ""
tags:
- Wearables
- Stack Network
- Google APIs
- Fitness
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-fit/apis.yaml
specificationVersion: "0.14"
apis:
- name: Google Fit API
  description: Google Fit is an open ecosystem that allows developers to upload fitness
    data to a central repository where users can access their data from different
    devices and apps in one location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: ""
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-fit/userid-datasources-datasourceid-datasets-datasetid-patch.md
- name: Google Fit API Get All Data Source Datasets
  description: Returns a dataset containing all data points whose start and end times
    overlap with the specified range of the dataset minimum start time and maximum
    end time. Specifically, any data point whose start time is less than or equal
    to the dataset end time and whose end time is greater than or equal to the dataset
    start time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: http:://www.googleapis.com//fitness/v1/users
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-fit/userid-datasources-datasourceid-datasets-datasetid-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/google-fit/userid-datasources-datasourceid-datasets-datasetid-get-postman.md
x-common:
- type: x-authentication
  url: https://developers.google.com/fit/android/get-api-key
- type: x-getting-started
  url: https://developers.google.com/fit/rest/v1/get-started
- type: x-website
  url: https://developers.google.com/fit/overview
- type: x-authentication
  url: https://developers.google.com/fit/android/get-api-key
- type: x-getting-started
  url: https://developers.google.com/fit/rest/v1/get-started
- type: x-website
  url: https://developers.google.com/fit/overview
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---