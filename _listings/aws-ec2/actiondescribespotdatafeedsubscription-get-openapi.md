---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Describe Spot Datafeed Subscription
  version: 1.0.0
  description: Describes the data feed for Spot instances.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateSpotDatafeedSubscription:
    get:
      summary: Create Spot Datafeed Subscription
      description: Creates a data feed for Spot instances, enabling you to view Spot
        instance usage logs.
      operationId: createspotdatafeedsubscription
      x-api-path-slug: actioncreatespotdatafeedsubscription-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnet
  /?Action=DeleteSpotDatafeedSubscription:
    get:
      summary: Delete Spot Datafeed Subscription
      description: Deletes the data feed for Spot instances.
      operationId: deletespotdatafeedsubscription
      x-api-path-slug: actiondeletespotdatafeedsubscription-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Data Feed Subscription
  /?Action=DescribeSpotDatafeedSubscription:
    get:
      summary: Describe Spot Datafeed Subscription
      description: Describes the data feed for Spot instances.
      operationId: describespotdatafeedsubscription
      x-api-path-slug: actiondescribespotdatafeedsubscription-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: SpotInstanceRequestId.N
        description: One or more Spot instance request IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Data Feed
  /?Action=GetPasswordData:
    get:
      summary: Get Password Data
      description: Retrieves the encrypted administrator password for an instance
        running Windows.
      operationId: getpassworddata
      x-api-path-slug: actiongetpassworddata-get
      parameters:
      - in: query
        name: Attribute
        description: The name of the attribute
        type: string
      - in: query
        name: BlockDeviceMapping.N
        description: Modifies the DeleteOnTermination attribute for volumesthat are
          currently attached
        type: string
      - in: query
        name: DisableApiTermination
        description: If the value is true, you cant terminate the instance using the
          Amazon EC2      console, CLI, or API; otherwise, you can
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: EbsOptimized
        description: Specifies whether the instance is optimized for EBS I/O
        type: string
      - in: query
        name: EnaSupport
        description: Set to true to enable enhanced networking with ENA for the instance
        type: string
      - in: query
        name: GroupId.N
        description: '[EC2-VPC] Changes the security groups of the instance'
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: InstanceInitiatedShutdownBehavior
        description: Specifies whether an instance stops or terminates when you initiate
          shutdown from the instance (using the operating system command for system
          shutdown)
        type: string
      - in: query
        name: InstanceType
        description: Changes the instance type to the specified value
        type: string
      - in: query
        name: Kernel
        description: Changes the instances kernel to the specified value
        type: string
      - in: query
        name: Ramdisk
        description: Changes the instances RAM disk to the specified value
        type: string
      - in: query
        name: SourceDestCheck
        description: Specifies whether source/destination checking is enabled
        type: string
      - in: query
        name: SriovNetSupport
        description: Set to simple to enable enhanced networking with the Intel 82599
          Virtual Function interface for the instance
        type: string
      - in: query
        name: UserData
        description: Changes the instances user data to the specified value
        type: string
      - in: query
        name: Value
        description: A new value for the attribute
        type: string
      responses:
        200:
          description: OK
      tags:
      - Password Data
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