{
  "info": {
    "name": "Google Fit API Delete Data Source",
    "_postman_id": "a3701cc6-ea4e-48c7-94c2-6a0d56be7b16",
    "description": "Deletes the specified data source. The request will fail if the data source contains any data points.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "data source",
      "item": [
        {
          "id": "d3b337e3-471a-4998-92b5-62278eacc011",
          "name": "fitness.users.dataSources.delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "fitness",
                "v1",
                "users",
                ":userId/dataSources/:dataSourceId"
              ],
              "variable": [
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
            "description": "Deletes the specified data source"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "019658d9-c291-4c26-a036-6029556037c3"
            }
          ]
        }
      ]
    }
  ]
}