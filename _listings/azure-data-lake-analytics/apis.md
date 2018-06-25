---
name: Azure Data Lake Analytics
x-slug: azure-data-lake-analytics
description: The Data Lake analytics service is a new distributed analytics service
  built on Apache YARN that dynamically scales so you can focus on your business goals,
  not on distributed infrastructure. Instead of deploying, configuring and tuning
  hardware, you write queries to transform your data and extract valuable insights.
  The analytics service can handle jobs of any scale instantly by simply setting the
  dial for how much power you need. You only pay for your job when it is running making
  it cost-effective. The analytics service supports Azure Active Directory letting
  you simply manage access and roles, integrated with your on-premises identity system.
  It also includes U-SQL, a language that unifies the benefits of SQL with the expressive
  power of user code. U-SQL&rsquo;s scalable distributed runtime enables you to efficiently
  analyze data in the store and across SQL Servers in Azure, Azure SQL Database and
  Azure SQL Data Warehouse.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Data
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Data Lake Analytics API Data Lake Store Accounts Get
  x-api-slug: azure-data-lake-analytics-api
  description: Gets the specified Data Lake Store account details in the specified
    Data Lake Analytics account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/{dataLakeStoreAccountName}
  tags: Data Lake Ste Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get-openapi.md
- name: Azure Data Lake Analytics API Data Lake Store Accounts Delete
  x-api-slug: azure-data-lake-analytics-api
  description: Updates the Data Lake Analytics account specified to remove the specified
    Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/{dataLakeStoreAccountName}
  tags: Data Lake Ste Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-delete-openapi.md
- name: Azure Data Lake Analytics API Data Lake Store Accounts Add
  x-api-slug: azure-data-lake-analytics-api
  description: Updates the specified Data Lake Analytics account to include the additional
    Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/{dataLakeStoreAccountName}
  tags: Data Lake Ste Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-put-openapi.md
- name: Azure Data Lake Analytics API Data Lake Store Accounts List By Account
  x-api-slug: azure-data-lake-analytics-api
  description: Gets the first page of Data Lake Store accounts linked to the specified
    Data Lake Analytics account. The response includes a link to the next page, if
    any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/
  tags: Data Lake Ste Account Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccounts-get-openapi.md
- name: Azure Data Lake Analytics API Catalog Get External Data Source
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the specified external data source from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/externaldatasources/{externalDataSourceName}
  tags: Catalog External Data Source
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameexternaldatasourcesexternaldatasourcename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameexternaldatasourcesexternaldatasourcename-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List External Data Sources
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of external data sources from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/externaldatasources
  tags: Catalog External Data Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameexternaldatasources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameexternaldatasources-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List Table Statistics By Database And
    Schema
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of all table statistics within the specified schema
    from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/schemas/{schemaName}/statistics
  tags: Catalog Table Statistic Database Schema
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanamestatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameschemasschemanamestatistics-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List Table Statistics By Database
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of all statistics in a database from the Data Lake
    Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/statistics
  tags: Catalog Table Statistic Database
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamestatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenamestatistics-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List Tables By Database
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of all tables in a database from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/tables
  tags: Catalog Table Database
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametables-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List Table Valued Functions By Database
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of all table valued functions in a database from
    the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/tablevaluedfunctions
  tags: Catalog Table Valued Function Database
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametablevaluedfunctions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenametablevaluedfunctions-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List Views By Database
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of all views in a database from the Data Lake Analytics
    catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}/views
  tags: Catalog View Database
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasenameviews-get-openapi.md
- name: Azure Data Lake Analytics API Catalog Get Database
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the specified database from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases/{databaseName}
  tags: Catalog Database
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabasesdatabasename-get-openapi.md
- name: Azure Data Lake Analytics API Catalog List Databases
  x-api-slug: azure-data-lake-analytics-api
  description: Retrieves the list of databases from the Data Lake Analytics catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////catalog/usql/databases
  tags: Catalog Databases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/catalogusqldatabases-get-openapi.md
- name: Azure Data Lake Analytics API Job Get Debug Data Path
  x-api-slug: azure-data-lake-analytics-api
  description: Gets the job debug data information specified by the job ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: ://////Jobs/{jobIdentity}/GetDebugDataPath
  tags: Job Debug Data Path
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/jobsjobidentitygetdebugdatapath-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/jobsjobidentitygetdebugdatapath-get-openapi.md
- name: Azure Data Lake Analytics API
  x-api-slug: azure-data-lake-analytics-api
  description: The Data Lake analytics service is a new distributed analytics service
    built on Apache YARN that dynamically scales so you can focus on your business
    goals, not on distributed infrastructure. Instead of deploying, configuring and
    tuning hardware, you write queries to transform your data and extract valuable
    insights. The analytics service can handle jobs of any scale instantly by simply
    setting the dial for how much power you need. You only pay for your job when it
    is running making it cost-effective. The analytics service supports Azure Active
    Directory letting you simply manage access and roles, integrated with your on-premises
    identity system. It also includes U-SQL, a language that unifies the benefits
    of SQL with the expressive power of user code. U-SQL&rsquo;s scalable distributed
    runtime enables you to efficiently analyze data in the store and across SQL Servers
    in Azure, Azure SQL Database and Azure SQL Data Warehouse.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-lake-analytics-05.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-analytics/
  baseURL: :////
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/azure-data-lake-analytics/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/data-lake-analytics/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/data-lake-analytics/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/data-lake-analytics/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/data-lake-analytics/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---