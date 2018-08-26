{
  "info": {
    "name": "Kaltura VPaaS Get Service Data Action Get",
    "_postman_id": "25dae7b7-3673-442e-a820-ed9a952dc32e",
    "description": "Get data entry by ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "cb709d0f-7560-469c-a1aa-87bc40f04e07",
          "name": "baseEntry.getContextData",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/baseentry/action/getContextData?contextDataParams[contexts]=%7B%7D&contextDataParams[flavorAssetId]=%7B%7D&contextDataParams[flavorTags]=%7B%7D&contextDataParams[hashes]=%7B%7D&contextDataParams[ip]=%7B%7D&contextDataParams[ks]=%7B%7D&contextDataParams[mediaProtocol]=%7B%7D&contextDataParams[objectType]=%7B%7D&contextDataParams[referrer]=%7B%7D&contextDataParams[streamerType]=%7B%7D&contextDataParams[time]=%7B%7D&contextDataParams[userAgent]=%7B%7D&entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This action delivers entry-related data, based on the user's context: access control, restriction, playback format and storage information."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0956bfb7-2318-42d1-b885-20ccddbb46c0"
            }
          ]
        },
        {
          "id": "76838e0e-0d06-4039-a3a5-97abc85f521b",
          "name": "entryDistribution.serveReturnedData",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/serveReturnedData?actionType=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Serves entry distribution returned data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d56e2b85-c026-41a6-a7a1-0a1b42906e91"
            }
          ]
        },
        {
          "id": "2f652290-f413-416e-81ed-f698ce726bd9",
          "name": "entryDistribution.serveSentData",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/serveSentData?actionType=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Serves entry distribution sent data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d702b05-43d7-4416-aa19-2179f18f7208"
            }
          ]
        },
        {
          "id": "f6365062-e3f7-4dfb-bce2-3ee86f18ba08",
          "name": "data.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/data/action/add?dataEntry[accessControlId]=%7B%7D&dataEntry[adminTags]=%7B%7D&dataEntry[categoriesIds]=%7B%7D&dataEntry[categories]=%7B%7D&dataEntry[conversionProfileId]=%7B%7D&dataEntry[creatorId]=%7B%7D&dataEntry[dataContent]=%7B%7D&dataEntry[description]=%7B%7D&dataEntry[displayInSearch]=%7B%7D&dataEntry[endDate]=%7B%7D&dataEntry[entitledUsersEdit]=%7B%7D&dataEntry[entitledUsersPublish]=%7B%7D&dataEntry[groupId]=%7B%7D&dataEntry[licenseType]=%7B%7D&dataEntry[name]=%7B%7D&dataEntry[operationAttributes]=%7B%7D&dataEntry[parentEntryId]=%7B%7D&dataEntry[partnerData]=%7B%7D&dataEntry[partnerSortValue]=%7B%7D&dataEntry[redirectEntryId]=%7B%7D&dataEntry[referenceId]=%7B%7D&dataEntry[retrieveDataContentByGet]=%7B%7D&dataEntry[startDate]=%7B%7D&dataEntry[tags]=%7B%7D&dataEntry[templateEntryId]=%7B%7D&dataEntry[type]=%7B%7D&dataEntry[userId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new data entry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "017ad342-83d9-400a-a170-3989eb864d80"
            }
          ]
        },
        {
          "id": "badf81e8-d6e6-42be-97b1-08f279ecbd8c",
          "name": "data.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/data/action/delete?entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a data entry."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79e10cc8-5285-44c8-9ac1-892034da5fb8"
            }
          ]
        },
        {
          "id": "435bb402-8792-4799-a9ad-cd6c3143896b",
          "name": "data.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/data/action/get?entryId=%7B%7D&No Name=%7B%7D&version=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get data entry by ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aff48a9d-52fc-4c1b-bc90-fb25a853237c"
            }
          ]
        }
      ]
    }
  ]
}