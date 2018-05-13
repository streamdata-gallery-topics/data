{
  "info": {
    "name": "Microsoft Graph API Chart Set Data",
    "_postman_id": "7ec93b2f-2a63-427c-b9d9-ebcce744fa02",
    "description": "Chart: setData Resets the source data for the chart.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "chart",
      "item": [
        {
          "id": "58feb251-a192-41b5-a09b-a00b85fd40b6",
          "name": "Chart:SetData",
          "request": {
            "url": "http://graph.microsoft.com/, Set, Data",
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Chart: setData Resets the source data for the chart"
          },
          "response": [
            {
              "status": "Successful Response",
              "code": 200,
              "name": "Response_200",
              "id": "c5d041e1-0542-4cc5-a151-aeaa97c98653"
            }
          ]
        }
      ]
    }
  ]
}