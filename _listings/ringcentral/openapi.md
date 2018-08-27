swagger: "2.0"
x-collection-name: RingCentral
x-complete: 1
info:
  title: RingCentral Connect Platform API Explorer
  description: this-is-an-interactive-api-explorer-for-the-ringcentral-connect-platform--to-use-this-service-you-will-need-to-have-a-developer-account---links--a-hrefhttpsnetstorage-ringcentral-comdpwapiexplorerrcplatform-basic-ymlv20180514092722-target-blankringcentral-api-specaspannbspnbspopenapi-fka-swagger-formatnbspnbspnbspnbspspana-hrefhttpsgithub-comoaiopenapispecification-target-blanklearn-more-about-openapia
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/recording/{recordingId}/content:
    get:
      summary: Get Call Recordings Data
      description: "Returns media content of a call recording.\nApp Permission\nReadCallRecording\nUser
        Permission\nReadCallRecording\nUsage Plan Group\nHeavy\nError Codes\n\n \n
        \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nAGW-402\nInvalid
        Authorization header\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-149\nUnparsable
        access token\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadCallRecording]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found\n\n\n416\nCMN-107\nRequested
        range not satisfiable"
      operationId: listCallRecordingData
      x-api-path-slug: restapiv1-0accountaccountidrecordingrecordingidcontent-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: recordingId
        description: Internal identifier of a recording (returned in Call Log)
      responses:
        200:
          description: OK
      tags:
      - Call
      - Recordings
      - Data