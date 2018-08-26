{
  "info": {
    "name": "Plentymarkets Get supplier data for a variation",
    "_postman_id": "e47ee9cc-882b-4d67-8916-b6a2b79567dd",
    "description": "Gets the data for a supplier linked to a variation. The ID of the variation and the ID of the link between the variation and the supplier must be specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "3d329e47-2a5c-4bfb-8296-18f2a5d0fb48",
          "name": "getRestItemsVariationsVariationVariationSuppliers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_suppliers"
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
            "description": "Lists all supplier data linked to a variation. The ID of the variation must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8bf3896-675c-4a74-8fb4-45142abe1685"
            }
          ]
        }
      ]
    },
    {
      "name": "Link",
      "item": [
        {
          "id": "7768fc86-7ced-47ae-aa8f-d8a2be18e349",
          "name": "postRestItemsVariationsVariationVariationSuppliers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_suppliers"
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
            "description": "Creates a link between a variation and a supplier and adds supplier data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f73fdbec-7296-4806-aed5-e50a4164a3b5"
            }
          ]
        },
        {
          "id": "11dd8af7-fbf7-4b74-a32a-aa30ad9199c2",
          "name": "deleteRestItemsVariationsVariationVariationSuppliersVariationsupplier",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_suppliers/:variationSupplierId"
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
                  "id": "variationSupplierId",
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
            "description": "Deletes a link between a variation and a supplier. The ID of the variation and the ID of the link between the variation and the supplier must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2b20e9f-d96a-4e55-852d-aa6be3663a74"
            }
          ]
        }
      ]
    },
    {
      "name": "Supplier",
      "item": [
        {
          "id": "33d4b5e0-db2a-4902-91ea-7ff5dca91c58",
          "name": "getRestItemsVariationsVariationVariationSuppliersVariationsupplier",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_suppliers/:variationSupplierId"
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
                  "id": "variationSupplierId",
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
            "description": "Gets the data for a supplier linked to a variation. The ID of the variation and the ID of the link between the variation and the supplier must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f5ac1a0-ef83-488e-9af3-569be1419de0"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "ae96c541-3c60-472b-8094-0f1bd4e6809a",
          "name": "putRestItemsVariationsVariationVariationSuppliersVariationsupplier",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/variation_suppliers/:variationSupplierId"
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
                  "id": "variationSupplierId",
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
            "description": "Updates the data of a supplier linked to a variation."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13b0bfaf-9473-428f-be17-123a6db2c149"
            }
          ]
        }
      ]
    }
  ]
}