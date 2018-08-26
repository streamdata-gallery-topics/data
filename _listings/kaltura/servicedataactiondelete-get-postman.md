{
  "info": {
    "name": "Kaltura VPaaS Get Service Data Action Delete",
    "_postman_id": "eb3ebc34-9b0f-4933-8f2c-d400b3297610",
    "description": "Delete a data entry.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "130bf557-7ab6-4759-ac1b-01aa1027c7ab",
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
              "id": "25df3483-f287-49fb-8016-0dc669b622b4"
            }
          ]
        },
        {
          "id": "0ff993dc-df54-4cbd-ae68-10f5b9446fc7",
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
              "id": "d4d6be61-7b92-4278-a451-9b0ca92795c4"
            }
          ]
        },
        {
          "id": "a5e7c5d2-b7a0-470a-b90d-d9ac633acf0a",
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
              "id": "1cf3c016-35b3-4d1e-acec-66d01873897b"
            }
          ]
        },
        {
          "id": "18f628e0-4074-407d-91db-7a832832130e",
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
              "id": "bcf38dec-fe09-4431-b58b-ad0b211e7da2"
            }
          ]
        },
        {
          "id": "05aaa668-ee30-49ae-9579-5ad9a6bedac2",
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
              "id": "f96a02d7-6284-4cff-8d61-86102ba1b3b3"
            }
          ]
        }
      ]
    }
  ]
}