---
name: Click Meter
x-slug: click-meter
description: ClickMeter was founded in 2012 as a byproduct of an experienced web-marketing
  agency. The ClickMeter System was initially a web tool created to address the needs
  of our agency to precisely count and track the web-marketing actions we performed
  for our customers.The system evolved rapidly, and emerged as one of the most widely
  used software solutions in our agency to collect, analyze, and share data for and
  with our customers. After few years after the development of the first ClickMeter
  system, we decided to go live with a service that can be useful to everyone involved
  in web-marketing activities.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Data
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/apis.md
specificationVersion: "0.14"
apis:
- name: Click Meter Retrieve statistics about a subset of datapoints for a timeframe
    with datapoints data
  x-api-slug: click-meter
  description: Retrieve statistics about a subset of datapoints for a timeframe with
    datapoints data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////aggregated/summary/datapoints
  tags: Aggregated,Summary,Datapoints
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/aggregatedsummarydatapoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/aggregatedsummarydatapoints-get-openapi.md
- name: Click Meter Retrieve a list of datapoints connected to this conversion
  x-api-slug: click-meter
  description: Retrieve a list of datapoints connected to this conversion.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints
  tags: Conversions,ConversionId,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/conversionsconversioniddatapoints-get-openapi.md
- name: Click Meter Modify the association between a conversion and multiple datapoints
  x-api-slug: click-meter
  description: Modify the association between a conversion and multiple datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints/batch/patch
  tags: Conversions,ConversionId,Datapoints,Batch,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/conversionsconversioniddatapointsbatchpatch-put-openapi.md
- name: Click Meter Retrieve a count of datapoints connected to this conversion
  x-api-slug: click-meter
  description: Retrieve a count of datapoints connected to this conversion.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints/count
  tags: Conversions,ConversionId,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/conversionsconversioniddatapointscount-get-openapi.md
- name: Click Meter Modify the association between a conversion and a datapoint
  x-api-slug: click-meter
  description: Modify the association between a conversion and a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints/patch
  tags: Conversions,ConversionId,Datapoints,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/conversionsconversioniddatapointspatch-put-openapi.md
- name: Click Meter List of all the datapoints associated to the user
  x-api-slug: click-meter
  description: List of all the datapoints associated to the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints
  tags: Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapoints-get-openapi.md
- name: Click Meter Create a datapoint
  x-api-slug: click-meter
  description: Create a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints
  tags: Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapoints-post-openapi.md
- name: Click Meter Retrieve statistics about this customer for a timeframe by groups
  x-api-slug: click-meter
  description: Retrieve statistics about this customer for a timeframe by groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/aggregated
  tags: Datapoints,Aggregated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsaggregated-get-openapi.md
- name: Click Meter Retrieve statistics about all datapoints of this customer for
    a timeframe grouped by some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about all datapoints of this customer for a timeframe
    grouped by some temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/aggregated/list
  tags: Datapoints,Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsaggregatedlist-get-openapi.md
- name: Click Meter Delete multiple datapoints
  x-api-slug: click-meter
  description: Delete multiple datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/batch
  tags: Datapoints,Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsbatch-delete-openapi.md
- name: Click Meter Update multiple datapoints
  x-api-slug: click-meter
  description: Update multiple datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/batch
  tags: Datapoints,Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsbatch-post-openapi.md
- name: Click Meter Create multiple datapoints
  x-api-slug: click-meter
  description: Create multiple datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/batch
  tags: Datapoints,Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsbatch-put-openapi.md
- name: Click Meter Count the datapoints associated to the user
  x-api-slug: click-meter
  description: Count the datapoints associated to the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/count
  tags: Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointscount-get-openapi.md
- name: Click Meter Delete a datapoint
  x-api-slug: click-meter
  description: Delete a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}
  tags: Datapoints,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsid-delete-openapi.md
- name: Click Meter Get a datapoint
  x-api-slug: click-meter
  description: Get a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}
  tags: Datapoints,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsid-get-openapi.md
- name: Click Meter Update a datapoint
  x-api-slug: click-meter
  description: Update a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}
  tags: Datapoints,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsid-post-openapi.md
- name: Click Meter Retrieve statistics about this datapoint for a timeframe
  x-api-slug: click-meter
  description: Retrieve statistics about this datapoint for a timeframe.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/aggregated
  tags: Datapoints,Id,Aggregated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsidaggregated-get-openapi.md
- name: Click Meter Retrieve statistics about this datapoint for a timeframe grouped
    by some temporal entity (day/week/month)
  x-api-slug: click-meter
  description: Retrieve statistics about this datapoint for a timeframe grouped by
    some temporal entity (day/week/month).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/aggregated/list
  tags: Datapoints,Id,Aggregated,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsidaggregatedlist-get-openapi.md
- name: Click Meter Fast switch the "favourite" field of a datapoint
  x-api-slug: click-meter
  description: Fast switch the "favourite" field of a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/favourite
  tags: Datapoints,Id,Favourite
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsidfavourite-put-openapi.md
- name: Click Meter Retrieve the list of events related to this datapoint.
  x-api-slug: click-meter
  description: Retrieve the list of events related to this datapoint..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/hits
  tags: Datapoints,Id,Hits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsidhits-get-openapi.md
- name: Click Meter Fast patch the "notes" field of a datapoint
  x-api-slug: click-meter
  description: Fast patch the "notes" field of a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/notes
  tags: Datapoints,Id,Notes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsidnotes-put-openapi.md
- name: Click Meter Retrieve a top report connected to this datapoint
  x-api-slug: click-meter
  description: Retrieve a top report connected to this datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/{id}/reports
  tags: Datapoints,Id,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/datapointsidreports-get-openapi.md
- name: Click Meter List of all the datapoints associated to the user in this group.
  x-api-slug: click-meter
  description: List of all the datapoints associated to the user in this group..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/datapoints
  tags: Groups,Id,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/groupsiddatapoints-get-openapi.md
- name: Click Meter Create a datapoint in this group
  x-api-slug: click-meter
  description: Create a datapoint in this group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/datapoints
  tags: Groups,Id,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/groupsiddatapoints-post-openapi.md
- name: Click Meter Count the datapoints associated to the user in this group.
  x-api-slug: click-meter
  description: Count the datapoints associated to the user in this group..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/datapoints/count
  tags: Groups,Id,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/groupsiddatapointscount-get-openapi.md
- name: Click Meter List of all the datapoints associated to the retargeting script.
  x-api-slug: click-meter
  description: List of all the datapoints associated to the retargeting script..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/{id}/datapoints
  tags: Retargeting,Id,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/retargetingiddatapoints-get-openapi.md
- name: Click Meter Count the datapoints associated to the retargeting script.
  x-api-slug: click-meter
  description: Count the datapoints associated to the retargeting script..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/{id}/datapoints/count
  tags: Retargeting,Id,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/retargetingiddatapointscount-get-openapi.md
- name: Click Meter Delete the association of this tag with all datapoints
  x-api-slug: click-meter
  description: Delete the association of this tag with all datapoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints
  tags: Tags,TagId,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/tagstagiddatapoints-delete-openapi.md
- name: Click Meter List of all the datapoints associated to the user filtered by
    this tag
  x-api-slug: click-meter
  description: List of all the datapoints associated to the user filtered by this
    tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints
  tags: Tags,TagId,Datapoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/tagstagiddatapoints-get-openapi.md
- name: Click Meter Count the datapoints associated to the user filtered by this tag
  x-api-slug: click-meter
  description: Count the datapoints associated to the user filtered by this tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints/count
  tags: Tags,TagId,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/tagstagiddatapointscount-get-openapi.md
- name: Click Meter Associate/Deassociate a tag with a datapoint
  x-api-slug: click-meter
  description: Associate/deassociate a tag with a datapoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints/patch
  tags: Tags,TagId,Datapoints,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/tagstagiddatapointspatch-put-openapi.md
- name: Click Meter
  x-api-slug: click-meter
  description: ClickMeter was founded in 2012 as a byproduct of an experienced web-marketing
    agency. The ClickMeter System was initially a web tool created to address the
    needs of our agency to precisely count and track the web-marketing actions we
    performed for our customers.The system evolved rapidly, and emerged as one of
    the most widely used software solutions in our agency to collect, analyze, and
    share data for and with our customers. After few years after the development of
    the first ClickMeter system, we decided to go live with a service that can be
    useful to everyone involved in web-marketing activities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80//
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/click-meter/openapi.md
x-common:
- type: x-blog
  url: https://blog.clickmeter.com/
- type: x-pricing
  url: http://clickmeter.com/pricing-signup
- type: x-support
  url: https://support.clickmeter.com/hc/en-us
- type: x-terms-of-service
  url: http://clickmeter.com/terms-conditions
- type: x-twitter
  url: https://twitter.com/clickmeter
- type: x-website
  url: http://clickmeter.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---