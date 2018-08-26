{
  "info": {
    "name": "Azure Data Lake Analytics API Data Lake Store Accounts Delete",
    "_postman_id": "9f80a2c9-ccc8-49dd-86a8-c596a1bd4895",
    "description": "Updates the Data Lake Analytics account specified to remove the specified Data Lake Store account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "data lake ste account",
      "item": [
        {
          "id": "d9c63211-e231-44a9-a8e6-e4e4b3299a10",
          "name": "DataLakeStoreAccounts_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the Data Lake Analytics account specified to remove the specified Data Lake Store account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7540afbf-ff23-447d-8e13-d4cedcef5cfe"
            }
          ]
        }
      ]
    }
  ]
}