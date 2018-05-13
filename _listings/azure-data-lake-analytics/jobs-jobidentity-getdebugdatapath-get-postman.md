{
  "info": {
    "name": "Azure Data Lake Analytics API Job Get Debug Data Path",
    "_postman_id": "7ca27b73-21e4-4d54-9d54-509c76ee9832",
    "description": "Gets the job debug data information specified by the job ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "job debug data path",
      "item": [
        {
          "id": "19a84b2b-d121-48f5-a5ab-286f37dc6ba4",
          "name": "Job_GetDebugDataPath",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "Jobs/:jobIdentity/GetDebugDataPath"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "jobIdentity",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the job debug data information specified by the job ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "679c17dc-8610-4061-a5d3-7d812d8361e4"
            }
          ]
        }
      ]
    }
  ]
}