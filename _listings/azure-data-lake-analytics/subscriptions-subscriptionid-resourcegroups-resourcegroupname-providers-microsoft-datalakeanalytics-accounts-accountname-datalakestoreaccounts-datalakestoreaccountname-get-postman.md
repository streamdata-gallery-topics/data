{
  "info": {
    "name": "Azure Data Lake Analytics API Data Lake Store Accounts Get",
    "_postman_id": "e623b548-aa9d-4ef4-b15b-ab4cbeef61ab",
    "description": "Gets the specified Data Lake Store account details in the specified Data Lake Analytics account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "data lake ste account",
      "item": [
        {
          "id": "307e5fd9-b842-42da-aaaf-86b875a55b74",
          "name": "DataLakeStoreAccounts_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.DataLakeAnalytics/accounts/:accountName/DataLakeStoreAccounts/:dataLakeStoreAccountName"
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
                  "id": "accountName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "dataLakeStoreAccountName",
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
            "description": "Gets the specified Data Lake Store account details in the specified Data Lake Analytics account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8df6450-90e2-4b3c-a992-f7bb19b4f4af"
            }
          ]
        }
      ]
    }
  ]
}