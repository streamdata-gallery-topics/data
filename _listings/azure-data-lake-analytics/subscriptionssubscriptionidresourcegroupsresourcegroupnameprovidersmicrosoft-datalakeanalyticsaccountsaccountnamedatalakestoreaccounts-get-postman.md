{
  "info": {
    "name": "Azure Data Lake Analytics API Data Lake Store Accounts List By Account",
    "_postman_id": "034f227b-ba9c-4beb-897b-b372670dca1f",
    "description": "Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account. The response includes a link to the next page, if any.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "data lake ste account account",
      "item": [
        {
          "id": "1d48e5c8-d812-4c52-a252-93b0c6d7a9fb",
          "name": "DataLakeStoreAccounts_ListByAccount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.DataLakeAnalytics/accounts/:accountName/DataLakeStoreAccounts/"
              ],
              "query": [
                {
                  "key": "$count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "$filter",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "$orderby",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "$select",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "$skip",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "$top",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1dd7596-4349-4fb4-9bfa-509e357863ac"
            }
          ]
        }
      ]
    }
  ]
}