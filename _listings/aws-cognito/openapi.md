---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteDataset:
    get:
      summary: Delete Dataset
      description: Deletes the specific dataset.
      operationId: deleteDataset
      x-api-path-slug: actiondeletedataset-get
      parameters:
      - in: query
        name: DatasetName
        description: A string of up to 128 characters
        type: string
      - in: query
        name: IdentityId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Dataset
  /?Action=DescribeDataset:
    get:
      summary: Describe Dataset
      description: Gets meta data about a dataset by identity and dataset name.
      operationId: describeDataset
      x-api-path-slug: actiondescribedataset-get
      parameters:
      - in: query
        name: DatasetName
        description: A string of up to 128 characters
        type: string
      - in: query
        name: IdentityId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Dataset
  /?Action=ListDatasets:
    get:
      summary: List Datasets
      description: Lists datasets for an identity.
      operationId: listDatasets
      x-api-path-slug: actionlistdatasets-get
      parameters:
      - in: query
        name: IdentityId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to be returned
        type: string
      - in: query
        name: NextToken
        description: A pagination token for obtaining the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Dataset
  /?Action=SubscribeToDataset:
    get:
      summary: Subscribe To Dataset
      description: Subscribes to receive notifications when a dataset is modified
        by another device.
      operationId: subscribeToDataset
      x-api-path-slug: actionsubscribetodataset-get
      parameters:
      - in: query
        name: DatasetName
        description: The name of the dataset to subcribe to
        type: string
      - in: query
        name: DeviceId
        description: The unique ID generated for this device by Cognito
        type: string
      - in: query
        name: IdentityId
        description: Unique ID for this identity
        type: string
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Dataset
  /?Action=UnsubscribeFromDataset:
    get:
      summary: Unsubscribe From Dataset
      description: Unsubscribes from receiving notifications when a dataset is modified
        by another device.
      operationId: unsubscribeFromDataset
      x-api-path-slug: actionunsubscribefromdataset-get
      parameters:
      - in: query
        name: DatasetName
        description: The name of the dataset from which to unsubcribe
        type: string
      - in: query
        name: DeviceId
        description: The unique ID generated for this device by Cognito
        type: string
      - in: query
        name: IdentityId
        description: Unique ID for this identity
        type: string
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Dataset
---