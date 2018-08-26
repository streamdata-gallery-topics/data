---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 0
info:
  title: Azure Data Lake Analytics API Data Lake Store Accounts List By Account
  description: Gets the first page of Data Lake Store accounts linked to the specified
    Data Lake Analytics account. The response includes a link to the next page, if
    any.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/{dataLakeStoreAccountName}
  : get:
      summary: Data Lake Store Accounts Get
      description: Gets the specified Data Lake Store account details in the specified
        Data Lake Analytics account.
      operationId: DataLakeStoreAccounts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to retrieve
          the Data Lake Store account details
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
    delete:
      summary: Data Lake Store Accounts Delete
      description: Updates the Data Lake Analytics account specified to remove the
        specified Data Lake Store account.
      operationId: DataLakeStoreAccounts_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to remove
          the Data Lake Store account
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to remove
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
    put:
      summary: Data Lake Store Accounts Add
      description: Updates the specified Data Lake Analytics account to include the
        additional Data Lake Store account.
      operationId: DataLakeStoreAccounts_Add
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to which to add the
          Data Lake Store account
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to add
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The details of the Data Lake Store account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/
  : get:
      summary: Data Lake Store Accounts List By Account
      description: Gets the first page of Data Lake Store accounts linked to the specified
        Data Lake Analytics account. The response includes a link to the next page,
        if any.
      operationId: DataLakeStoreAccounts_ListByAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccounts-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account for which to list
          Data Lake Store accounts
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account Account
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---