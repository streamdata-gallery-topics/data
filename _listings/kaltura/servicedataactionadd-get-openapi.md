---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Data Action Add
  description: Adds a new data entry
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/baseentry/action/getContextData:
    get:
      summary: Get Service Baseentry Action Getcontextdata
      description: 'This action delivers entry-related data, based on the user''s
        context: access control, restriction, playback format and storage information.'
      operationId: baseEntry.getContextData
      x-api-path-slug: servicebaseentryactiongetcontextdata-get
      parameters:
      - in: query
        name: contextDataParams[contexts]
      - in: query
        name: contextDataParams[flavorAssetId]
        description: Id of the current flavor
      - in: query
        name: contextDataParams[flavorTags]
        description: The tags of the flavors that should be used for playback
      - in: query
        name: contextDataParams[hashes]
      - in: query
        name: contextDataParams[ip]
        description: IP to be used to test geographic location conditions
      - in: query
        name: contextDataParams[ks]
        description: Kaltura session to be used to test session and user conditions
      - in: query
        name: contextDataParams[mediaProtocol]
        description: Protocol of the specific media object
      - in: query
        name: contextDataParams[objectType]
      - in: query
        name: contextDataParams[referrer]
        description: URL to be used to test domain conditions
      - in: query
        name: contextDataParams[streamerType]
        description: 'Playback streamer type: RTMP, HTTP, appleHttps, rtsp, sl'
      - in: query
        name: contextDataParams[time]
        description: Unix timestamp (In seconds) to be used to test entry scheduling,
          keep null to use now
      - in: query
        name: contextDataParams[userAgent]
        description: Browser or client application to be used to test agent conditions
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Baseentry
      - Action
      - GetContextData
  /service/contentdistribution_entrydistribution/action/serveReturnedData:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Servereturneddata
      description: Serves entry distribution returned data
      operationId: entryDistribution.serveReturnedData
      x-api-path-slug: servicecontentdistribution-entrydistributionactionservereturneddata-get
      parameters:
      - in: query
        name: actionType
        description: 'Enum Type: `KalturaDistributionAction`'
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - ServeReturnedData
  /service/contentdistribution_entrydistribution/action/serveSentData:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Servesentdata
      description: Serves entry distribution sent data
      operationId: entryDistribution.serveSentData
      x-api-path-slug: servicecontentdistribution-entrydistributionactionservesentdata-get
      parameters:
      - in: query
        name: actionType
        description: 'Enum Type: `KalturaDistributionAction`'
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - ServeSentData
  /service/data/action/add:
    get:
      summary: Get Service Data Action Add
      description: Adds a new data entry
      operationId: data.add
      x-api-path-slug: servicedataactionadd-get
      parameters:
      - in: query
        name: dataEntry[accessControlId]
        description: The Access Control ID assigned to this entry (null when not set,
          send -1 to remove)
      - in: query
        name: dataEntry[adminTags]
        description: Entry admin tags can be updated only by administrators
      - in: query
        name: dataEntry[categoriesIds]
        description: Comma separated list of ids of categories to which this entry
          belongs
      - in: query
        name: dataEntry[categories]
        description: Comma separated list of full names of categories to which this
          entry belongs
      - in: query
        name: dataEntry[conversionProfileId]
        description: Override the default ingestion profile
      - in: query
        name: dataEntry[creatorId]
        description: '`insertOnly`The ID of the user who created this entry'
      - in: query
        name: dataEntry[dataContent]
        description: The data of the entry
      - in: query
        name: dataEntry[description]
        description: Entry description
      - in: query
        name: dataEntry[displayInSearch]
        description: 'Enum Type: `KalturaEntryDisplayInSearchType`should we display
          this entry in search'
      - in: query
        name: dataEntry[endDate]
        description: Entry scheduling end date (null when not set, send -1 to remove)
      - in: query
        name: dataEntry[entitledUsersEdit]
        description: list of user ids that are entitled to edit the entry (no server
          enforcement) The difference between entitledUsersEdit and entitledUsersPublish
          is applicative only
      - in: query
        name: dataEntry[entitledUsersPublish]
        description: list of user ids that are entitled to publish the entry (no server
          enforcement) The difference between entitledUsersEdit and entitledUsersPublish
          is applicative only
      - in: query
        name: dataEntry[groupId]
      - in: query
        name: dataEntry[licenseType]
        description: 'Enum Type: `KalturaLicenseType`License type used for this entry'
      - in: query
        name: dataEntry[name]
        description: Entry name (Min 1 chars)
      - in: query
        name: dataEntry[operationAttributes]
      - in: query
        name: dataEntry[parentEntryId]
        description: ID of source root entry, used for defining entires association
      - in: query
        name: dataEntry[partnerData]
        description: Can be used to store various partner related data as a string
      - in: query
        name: dataEntry[partnerSortValue]
        description: Can be used to store various partner related data as a numeric
          value
      - in: query
        name: dataEntry[redirectEntryId]
        description: IF not empty, points to an entry ID the should replace this current
          entrys id
      - in: query
        name: dataEntry[referenceId]
        description: Entry external reference id
      - in: query
        name: dataEntry[retrieveDataContentByGet]
        description: '`insertOnly`indicator whether to return the object for get action
          with the dataContent field'
      - in: query
        name: dataEntry[startDate]
        description: Entry scheduling start date (null when not set, send -1 to remove)
      - in: query
        name: dataEntry[tags]
        description: Entry tags
      - in: query
        name: dataEntry[templateEntryId]
        description: '`insertOnly`Template entry id'
      - in: query
        name: dataEntry[type]
        description: 'Enum Type: `KalturaEntryType`The type of the entry, this is
          auto filled by the derived entry object'
      - in: query
        name: dataEntry[userId]
        description: The ID of the user who is the owner of this entry
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Data
      - Action
      - Add
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---