---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Update additional data of the shipping information
  description: Updates additional data of the shipping information. The ID of the
    order must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/addresses/{addressId}/related_data:
    get:
      summary: Find address data by address id
      description: Find address data by address id.
      operationId: getRestAccountsAddressesAddressRelatedData
      x-api-path-slug: restaccountsaddressesaddressidrelated-data-get
      parameters:
      - in: path
        name: addressId
      responses:
        200:
          description: OK
      tags:
      - Find
      - Address
      - Data
      - By
      - Address
      - Id
  /rest/accounts/contacts/group_functions:
    get:
      summary: List all group function related data
      description: Lists all data that is related to the contact group function contents.
      operationId: getRestAccountsContactsGroupFunctions
      x-api-path-slug: restaccountscontactsgroup-functions-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Group
      - Function
      - Related
      - Data
  /rest/accounts/contacts/{contactId}/related_data:
    get:
      summary: Return all contact related data
      description: Returns all contact related data.
      operationId: getRestAccountsContactsContactRelatedData
      x-api-path-slug: restaccountscontactscontactidrelated-data-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Return
      - ""
      - Contact
      - Related
      - Data
  /rest/items/{id}/variations/{variationId}/variation_sales_prices/{priceId}:
    put:
      summary: Update sales price data
      description: Updates sales price data linked to a variation. The ID of the sales
        price and the ID of the variation must be specified.
      operationId: putRestItemsVariationsVariationVariationSalesPricesPrice
      x-api-path-slug: restitemsidvariationsvariationidvariation-sales-pricespriceid-put
      parameters:
      - in: body
        name: /rest/items/{id}/variations/{variationId}/variation_sales_prices/{priceId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: priceId
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Price
      - Data
  /rest/items/{id}/variations/{variationId}/variation_warehouses/{warehouseId}:
    put:
      summary: Update warehouse data of a variation
      description: Updates the data of a warehouse linked to a variation. The ID of
        the variation and the ID of the warehouse must be specified.
      operationId: putRestItemsVariationsVariationVariationWarehousesWarehouse
      x-api-path-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-put
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Data
      - Of
      - Variation
  /rest/orders/{orderId}/shipping/shipping_information/additional_data:
    put:
      summary: Update additional data of the shipping information
      description: Updates additional data of the shipping information. The ID of
        the order must be specified.
      operationId: putRestOrdersOrderShippingShippingInformationAdditionalData
      x-api-path-slug: restordersorderidshippingshipping-informationadditional-data-put
      parameters:
      - in: path
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - Additional
      - Data
      - Of
      - Shipping
      - Information
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