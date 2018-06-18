---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 1
info:
  title: Kaltura VPaaS
  description: building-video-experiences-consists-of-ingesting-media-files-playing-back-videos-and-reviewing-usage-and-engagement-analytics--in-between-there-is-a-world-of-nuances-required-for-your-unique-usecase-and-application--kaltura-vpaas-is-built-on-the-principles-of-atomic-services-sdks-and-tools-that-allow-you-full-control-and-flexibility-over-every-element-and-process-in-your-medias-life-cycle-
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
  /service/data/action/delete:
    get:
      summary: Get Service Data Action Delete
      description: Delete a data entry.
      operationId: data.delete
      x-api-path-slug: servicedataactiondelete-get
      parameters:
      - in: query
        name: entryId
        description: Data entry id to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Data
      - Action
      - Delete
  /service/data/action/get:
    get:
      summary: Get Service Data Action Get
      description: Get data entry by ID.
      operationId: data.get
      x-api-path-slug: servicedataactionget-get
      parameters:
      - in: query
        name: entryId
        description: Data entry id
      - in: query
        name: No Name
      - in: query
        name: version
        description: Desired version of the data
      responses:
        200:
          description: OK
      tags:
      - Service
      - Data
      - Action
      - Get
  /service/data/action/list:
    get:
      summary: Get Service Data Action List
      description: List data entries by filter with paging support.
      operationId: data.list
      x-api-path-slug: servicedataactionlist-get
      parameters:
      - in: query
        name: filter[accessControlIdEqual]
      - in: query
        name: filter[accessControlIdIn]
      - in: query
        name: filter[adminTagsLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[adminTagsMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[adminTagsMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[categoriesFullNameIn]
      - in: query
        name: filter[categoriesIdsEmpty]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[categoriesIdsMatchAnd]
      - in: query
        name: filter[categoriesIdsMatchOr]
        description: All entries of the categories, excluding their child categories
      - in: query
        name: filter[categoriesIdsNotContains]
      - in: query
        name: filter[categoriesMatchAnd]
      - in: query
        name: filter[categoriesMatchOr]
        description: All entries within these categories or their child categories
      - in: query
        name: filter[categoriesNotContains]
      - in: query
        name: filter[categoryAncestorIdIn]
        description: All entries within this categoy or in child categories
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
        description: This filter parameter should be in use for retrieving only entries
          which were created at Kaltura system after a specific time/date (standard
          timestamp format)
      - in: query
        name: filter[createdAtLessThanOrEqual]
        description: This filter parameter should be in use for retrieving only entries
          which were created at Kaltura system before a specific time/date (standard
          timestamp format)
      - in: query
        name: filter[creatorIdEqual]
      - in: query
        name: filter[endDateGreaterThanOrEqualOrNull]
      - in: query
        name: filter[endDateGreaterThanOrEqual]
      - in: query
        name: filter[endDateLessThanOrEqualOrNull]
      - in: query
        name: filter[endDateLessThanOrEqual]
      - in: query
        name: filter[entitledUsersEditMatchAnd]
      - in: query
        name: filter[entitledUsersEditMatchOr]
      - in: query
        name: filter[entitledUsersPublishMatchAnd]
      - in: query
        name: filter[entitledUsersPublishMatchOr]
      - in: query
        name: filter[freeText]
      - in: query
        name: filter[groupIdEqual]
      - in: query
        name: filter[idEqual]
        description: This filter should be in use for retrieving only a specific entry
          (identified by its entryId)
      - in: query
        name: filter[idIn]
        description: This filter should be in use for retrieving few specific entries
          (string should include comma separated list of entryId strings)
      - in: query
        name: filter[idNotIn]
      - in: query
        name: filter[isRoot]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[moderationStatusEqual]
        description: 'Enum Type: `KalturaEntryModerationStatus`'
      - in: query
        name: filter[moderationStatusIn]
      - in: query
        name: filter[moderationStatusNotEqual]
        description: 'Enum Type: `KalturaEntryModerationStatus`'
      - in: query
        name: filter[moderationStatusNotIn]
      - in: query
        name: filter[nameEqual]
        description: This filter should be in use for retrieving entries with a specific
          name
      - in: query
        name: filter[nameLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[nameMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[nameMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[parentEntryIdEqual]
      - in: query
        name: filter[partnerIdEqual]
        description: This filter should be in use for retrieving only entries which
          were uploaded by/assigned to users of a specific Kaltura Partner (identified
          by Partner ID)
      - in: query
        name: filter[partnerIdIn]
        description: This filter should be in use for retrieving only entries within
          Kaltura network which were uploaded by/assigned to users of few Kaltura
          Partners  (string should include comma separated list of PartnerIDs)
      - in: query
        name: filter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: filter[partnerSortValueLessThanOrEqual]
      - in: query
        name: filter[redirectFromEntryId]
        description: The id of the original entry
      - in: query
        name: filter[referenceIdEqual]
      - in: query
        name: filter[referenceIdIn]
      - in: query
        name: filter[replacedEntryIdEqual]
      - in: query
        name: filter[replacedEntryIdIn]
      - in: query
        name: filter[replacementStatusEqual]
        description: 'Enum Type: `KalturaEntryReplacementStatus`'
      - in: query
        name: filter[replacementStatusIn]
      - in: query
        name: filter[replacingEntryIdEqual]
      - in: query
        name: filter[replacingEntryIdIn]
      - in: query
        name: filter[rootEntryIdEqual]
      - in: query
        name: filter[rootEntryIdIn]
      - in: query
        name: filter[searchTextMatchAnd]
        description: 'This filter should be in use for retrieving specific entries
          while search match the input string within all of the following metadata
          attributes: name, description, tags, adminTags'
      - in: query
        name: filter[searchTextMatchOr]
        description: 'This filter should be in use for retrieving specific entries
          while search match the input string within at least one of the following
          metadata attributes: name, description, tags, adminTags'
      - in: query
        name: filter[startDateGreaterThanOrEqualOrNull]
      - in: query
        name: filter[startDateGreaterThanOrEqual]
      - in: query
        name: filter[startDateLessThanOrEqualOrNull]
      - in: query
        name: filter[startDateLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaEntryStatus`This filter should be in use
          for retrieving only entries, at a specific {'
      - in: query
        name: filter[statusIn]
        description: This filter should be in use for retrieving only entries, at
          few specific {
      - in: query
        name: filter[statusNotEqual]
        description: 'Enum Type: `KalturaEntryStatus`This filter should be in use
          for retrieving only entries, not at a specific {'
      - in: query
        name: filter[statusNotIn]
        description: This filter should be in use for retrieving only entries, not
          at few specific {
      - in: query
        name: filter[tagsAdminTagsMultiLikeAnd]
      - in: query
        name: filter[tagsAdminTagsMultiLikeOr]
      - in: query
        name: filter[tagsAdminTagsNameMultiLikeAnd]
      - in: query
        name: filter[tagsAdminTagsNameMultiLikeOr]
      - in: query
        name: filter[tagsLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[tagsMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[tagsMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: filter[tagsNameMultiLikeAnd]
      - in: query
        name: filter[tagsNameMultiLikeOr]
      - in: query
        name: filter[totalRankGreaterThanOrEqual]
      - in: query
        name: filter[totalRankLessThanOrEqual]
      - in: query
        name: filter[typeEqual]
        description: 'Enum Type: `KalturaEntryType`'
      - in: query
        name: filter[typeIn]
        description: This filter should be in use for retrieving entries of few {
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[userIdEqual]
        description: This filter parameter should be in use for retrieving only entries,
          uploaded by/assigned to a specific user (identified by user Id)
      - in: query
        name: filter[userIdIn]
      - in: query
        name: filter[userIdNotIn]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Data
      - Action
      - List
---