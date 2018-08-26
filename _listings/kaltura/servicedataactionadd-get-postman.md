{
  "info": {
    "name": "Kaltura VPaaS Get Service Data Action Add",
    "_postman_id": "2b4a5ade-80e5-4397-9766-17292bde5d87",
    "description": "Adds a new data entry",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "d3c2e9cd-d06c-4692-b262-d74e64c3adea",
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
              "id": "42af5243-b350-42ab-bd7c-f025de5242e4"
            }
          ]
        },
        {
          "id": "5acfac4e-5d16-4cb6-88d9-dbe1326f287f",
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
              "id": "d66c95e2-39b9-4fcd-9056-64465eb88c53"
            }
          ]
        },
        {
          "id": "be2e7ffc-a870-4e2e-9f86-ce2f615b331f",
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
              "id": "e33e1e5e-13f4-4ed6-90b1-3626d35a4a83"
            }
          ]
        },
        {
          "id": "30502e87-e00f-4958-961c-30494495a3f9",
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
              "id": "6e0fb22d-4f9c-42ab-a653-828bd1cbe3d8"
            }
          ]
        }
      ]
    }
  ]
}