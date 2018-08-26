{
  "info": {
    "name": "Google Fit API Get All Data Source Datasets",
    "_postman_id": "3b71a0f3-2b64-48df-89f5-e2b0509e9ff4",
    "description": "Returns a dataset containing all data points whose start and end times overlap with the specified range of the dataset minimum start time and maximum end time. Specifically, any data point whose start time is less than or equal to the dataset end time and whose end time is greater than or equal to the dataset start time.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "dataset",
      "item": [
        {
          "id": "4866673f-3855-4985-9310-785e4b71b4db",
          "name": "fitness.users.dataSources.datasets.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "fitness",
                "v1",
                "users",
                ":userId/dataSources/:dataSourceId/datasets/:datasetId"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageToken",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "datasetId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "dataSourceId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "userId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a dataset containing all data points whose start and end times overlap with the specified range of the dataset minimum start time and maximum end time"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07dc81f1-5928-440c-be67-16fb327c91ae"
            }
          ]
        }
      ]
    }
  ]
}