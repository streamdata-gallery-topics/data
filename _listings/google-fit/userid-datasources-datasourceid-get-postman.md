{
  "info": {
    "name": "Google Fit API Get Data Source",
    "_postman_id": "d8909cb1-1c5a-4e9b-9be8-f58ce0e1f13e",
    "description": "Returns the specified data source.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "data source",
      "item": [
        {
          "id": "8df2fc67-c2c7-4dff-aaa8-5e468df59d56",
          "name": "fitness.users.dataSources.get",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the specified data source"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc815564-75e2-4253-8b8a-33699aa7b545"
            }
          ]
        }
      ]
    }
  ]
}