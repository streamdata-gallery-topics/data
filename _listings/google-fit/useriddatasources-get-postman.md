{
  "info": {
    "name": "Google Fit API Get Data Sources",
    "_postman_id": "89d09d04-ee64-4958-9602-cb0ebf90ac83",
    "description": "Lists all data sources that are visible to the developer, using the OAuth scopes provided. The list is not exhaustive; the user may have private data sources that are only visible to other developers, or calls using other scopes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "data source",
      "item": [
        {
          "id": "f5cbb817-4643-47b2-9885-e99cf055c82e",
          "name": "fitness.users.dataSources.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "fitness",
                "v1",
                "users",
                ":userId/dataSources"
              ],
              "query": [
                {
                  "key": "dataTypeName",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
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
            "description": "Lists all data sources that are visible to the developer, using the OAuth scopes provided"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "121ac391-1bdc-4ef6-bd9a-fbac2b7f7493"
            }
          ]
        }
      ]
    }
  ]
}