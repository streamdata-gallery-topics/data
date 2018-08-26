---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Data Action Get
  description: Get data entry by ID.
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