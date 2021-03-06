---
swagger: "2.0"
info:
  title: Google Fit API Update Data Source
  description: |-
    Updates the specified data source. The dataStreamId, dataType, type, dataStreamName, and device properties with the exception of version, cannot be modified.

    Data sources are identified by their dataStreamId.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /fitness/v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{userId}/dataSources/{dataSourceId}:
    put:
      summary: Update Data Source
      description: Updates the specified data source
      operationId: fitness.users.dataSources.update
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: dataSourceId
        description: The data stream ID of the data source to update
      - in: path
        name: userId
        description: Update the data source for the person identified
      responses:
        200:
          description: OK
      tags:
      - data source
definitions:
  AggregateBucket:
    properties:
      activity:
        description: This is a default description.
        type: put
      dataset:
        description: This is a default description.
        type: put
      endTimeMillis:
        description: This is a default description.
        type: put
      startTimeMillis:
        description: This is a default description.
        type: put
      type:
        description: This is a default description.
        type: put
  AggregateBy:
    properties:
      dataSourceId:
        description: This is a default description.
        type: put
      dataTypeName:
        description: This is a default description.
        type: put
  AggregateRequest:
    properties:
      aggregateBy:
        description: This is a default description.
        type: put
      endTimeMillis:
        description: This is a default description.
        type: put
      filteredDataQualityStandard:
        description: This is a default description.
        type: put
      startTimeMillis:
        description: This is a default description.
        type: put
  AggregateResponse:
    properties:
      bucket:
        description: This is a default description.
        type: put
  Application:
    properties:
      detailsUrl:
        description: This is a default description.
        type: put
      name:
        description: This is a default description.
        type: put
      packageName:
        description: This is a default description.
        type: put
      version:
        description: This is a default description.
        type: put
  BucketByActivity:
    properties:
      activityDataSourceId:
        description: This is a default description.
        type: put
      minDurationMillis:
        description: This is a default description.
        type: put
  BucketBySession:
    properties:
      minDurationMillis:
        description: This is a default description.
        type: put
  BucketByTime:
    properties:
      durationMillis:
        description: This is a default description.
        type: put
  BucketByTimePeriod:
    properties:
      timeZoneId:
        description: This is a default description.
        type: put
      type:
        description: This is a default description.
        type: put
      value:
        description: This is a default description.
        type: put
  DataPoint:
    properties:
      computationTimeMillis:
        description: This is a default description.
        type: put
      dataTypeName:
        description: This is a default description.
        type: put
      endTimeNanos:
        description: This is a default description.
        type: put
      modifiedTimeMillis:
        description: This is a default description.
        type: put
      originDataSourceId:
        description: This is a default description.
        type: put
      rawTimestampNanos:
        description: This is a default description.
        type: put
      startTimeNanos:
        description: This is a default description.
        type: put
      value:
        description: This is a default description.
        type: put
  DataSource:
    properties:
      dataQualityStandard:
        description: This is a default description.
        type: put
      dataStreamId:
        description: This is a default description.
        type: put
      dataStreamName:
        description: This is a default description.
        type: put
      name:
        description: This is a default description.
        type: put
      type:
        description: This is a default description.
        type: put
  DataType:
    properties:
      field:
        description: This is a default description.
        type: put
      name:
        description: This is a default description.
        type: put
  DataTypeField:
    properties:
      format:
        description: This is a default description.
        type: put
      name:
        description: This is a default description.
        type: put
      optional:
        description: This is a default description.
        type: put
  Dataset:
    properties:
      dataSourceId:
        description: This is a default description.
        type: put
      maxEndTimeNs:
        description: This is a default description.
        type: put
      minStartTimeNs:
        description: This is a default description.
        type: put
      nextPageToken:
        description: This is a default description.
        type: put
      point:
        description: This is a default description.
        type: put
  Device:
    properties:
      manufacturer:
        description: This is a default description.
        type: put
      model:
        description: This is a default description.
        type: put
      type:
        description: This is a default description.
        type: put
      uid:
        description: This is a default description.
        type: put
      version:
        description: This is a default description.
        type: put
  ListDataSourcesResponse:
    properties:
      dataSource:
        description: This is a default description.
        type: put
  ListSessionsResponse:
    properties:
      deletedSession:
        description: This is a default description.
        type: put
      hasMoreData:
        description: This is a default description.
        type: put
      nextPageToken:
        description: This is a default description.
        type: put
      session:
        description: This is a default description.
        type: put
  MapValue:
    properties:
      fpVal:
        description: This is a default description.
        type: put
  Session:
    properties:
      activeTimeMillis:
        description: This is a default description.
        type: put
      activityType:
        description: This is a default description.
        type: put
      description:
        description: This is a default description.
        type: put
      endTimeMillis:
        description: This is a default description.
        type: put
      id:
        description: This is a default description.
        type: put
      modifiedTimeMillis:
        description: This is a default description.
        type: put
      name:
        description: This is a default description.
        type: put
      startTimeMillis:
        description: This is a default description.
        type: put
  Value:
    properties:
      fpVal:
        description: This is a default description.
        type: put
      intVal:
        description: This is a default description.
        type: put
      mapVal:
        description: This is a default description.
        type: put
      stringVal:
        description: This is a default description.
        type: put
  ValueMapValEntry:
    properties:
      key:
        description: This is a default description.
        type: put
x-collection-name: Google Fit
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