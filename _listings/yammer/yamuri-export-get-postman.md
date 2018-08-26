{
  "info": {
    "name": "Yammer API Get Export Of Data",
    "_postman_id": "52d42b74-08ad-4c31-8817-d2dff4255d53",
    "description": "Exports data from Network",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "data",
      "item": [
        {
          "id": "aaf6db8c-60e5-47f2-81a7-6f78c27dd678",
          "name": "Get_Export of Data_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/export"
              ],
              "query": [
                {
                  "key": "include",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "include_ens",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "since",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "yamURI",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Exports data from Network"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd078657-8b17-4ef0-8fa1-139187254c3b"
            }
          ]
        }
      ]
    }
  ]
}