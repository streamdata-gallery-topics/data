{
  "info": {
    "name": "Plentymarkets Update warehouse data of a variation",
    "_postman_id": "5f671948-ef2c-494d-b5ab-c714a5199405",
    "description": "Updates the data of a warehouse linked to a variation. The ID of the variation and the ID of the warehouse must be specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Address",
      "item": [
        {
          "id": "95ed456f-40ba-42d4-b5c7-57101925b39f",
          "name": "postRestAccountsAddressesWarehouseRelations",
          "request": {
            "url": "http://example.com/rest/accounts/addresses/warehouse_relations",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Create an address warehouse relation."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88904832-9087-464c-ba4e-ad9986cca33e"
            }
          ]
        },
        {
          "id": "819019c7-ff99-402e-8f51-0ff8c4a77885",
          "name": "putRestAccountsAddressesWarehouseRelationsRelation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/accounts/addresses/warehouse_relations/:relationId"
              ],
              "variable": [
                {
                  "id": "relationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Updates an address warehouse relation. The ID of the relation must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43ffb1f7-faa3-484c-a7f3-462872c8b768"
            }
          ]
        },
        {
          "id": "fccc8559-3164-45ca-9cc2-9dec2fcbabab",
          "name": "deleteRestAccountsAddressesWarehouseRelationsRelation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/accounts/addresses/warehouse_relations/:relationId"
              ],
              "variable": [
                {
                  "id": "relationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an address warehouse relation. The ID of the relation must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bee9cceb-1a38-4e0f-be40-224f81b71086"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "51efdf63-5887-4167-b120-7eee807ace3d",
          "name": "getRestItemsVariationsVariationStock",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/stock"
              ],
              "query": [
                {
                  "key": "columns",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "itemId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "variationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Lists stock of a variation per warehouse. The ID of the item and the ID of the variation must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a32cdb11-516a-40c1-ba0e-39554fa92377"
            }
          ]
        }
      ]
    },
    {
      "name": "Link",
      "item": [
        {
          "id": "0e705a20-c234-4673-8d3f-801c13b40f49",
          "name": "postRestItemsVariationsVariationVariationWarehouses",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_warehouses"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "variationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a link between a variation and a warehouse and adds warehouse data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "957f2b0b-dab9-4133-be4d-70463ab6ca15"
            }
          ]
        },
        {
          "id": "f5f636e5-3757-4078-af19-dcd743da9048",
          "name": "deleteRestItemsVariationsVariationVariationWarehousesWarehouse",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_warehouses/:warehouseId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "variationId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "warehouseId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the link between a warehouse and a variation. The ID of the variation and the ID of the warehouse must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "386df0f2-b8b5-43df-a0b6-c78bdb675056"
            }
          ]
        }
      ]
    },
    {
      "name": "Warehouse",
      "item": [
        {
          "id": "56e63133-5926-4be6-bccb-14931b792642",
          "name": "getRestItemsVariationsVariationVariationWarehousesWarehouse",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_warehouses/:warehouseId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "variationId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "warehouseId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the data of a warehouse linked to a variation. The ID of the variation and the ID of the warehouse must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ad92b3e-5c65-40d8-bd27-683f4346118b"
            }
          ]
        },
        {
          "id": "5e353e7a-aaf4-4a44-9c75-69d7fdbd3a6c",
          "name": "putRestItemsVariationsVariationVariationWarehousesWarehouse",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_warehouses/:warehouseId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "variationId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "warehouseId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Updates the data of a warehouse linked to a variation. The ID of the variation and the ID of the warehouse must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51a0f741-d71f-42fd-b8f1-b5aed4931223"
            }
          ]
        }
      ]
    }
  ]
}