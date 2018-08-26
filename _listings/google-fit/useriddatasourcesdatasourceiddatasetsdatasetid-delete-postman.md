{
  "info": {
    "name": "Google Fit API Delete All Data Source Datasets",
    "_postman_id": "3e721959-cfec-437a-8814-d9faebf0b9eb",
    "description": "Performs an inclusive delete of all data points whose start and end times have any overlap with the time range specified by the dataset ID. For most data types, the entire data point will be deleted. For data types where the time span represents a consistent value (such as com.google.activity.segment), and a data point straddles either end point of the dataset, only the overlapping portion of the data point will be deleted.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "dataset",
      "item": [
        {
          "id": "fe455302-2c54-428c-a765-0c465e483a29",
          "name": "fitness.users.dataSources.datasets.delete",
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
                  "key": "currentTimeMillis",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "modifiedTimeMillis",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Performs an inclusive delete of all data points whose start and end times have any overlap with the time range specified by the dataset ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9abb12a-6edc-4cb9-9917-556901ab4e63"
            }
          ]
        }
      ]
    }
  ]
}