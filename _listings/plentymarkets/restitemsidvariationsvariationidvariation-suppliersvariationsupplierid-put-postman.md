{
  "info": {
    "name": "Plentymarkets Updates supplier data for a variation",
    "_postman_id": "8ba22b33-2e72-4f80-b20b-8651b3fd9c9c",
    "description": "Updates the data of a supplier linked to a variation.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Lists",
      "item": [
        {
          "id": "2281e7fa-c827-4770-8924-e4f7de44c7ee",
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
              "id": "72da7130-5158-4232-ada1-7314e99f5dac"
            }
          ]
        }
      ]
    },
    {
      "name": "Link",
      "item": [
        {
          "id": "36e434d9-4822-449a-aa2d-bfe4fb0cc852",
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
              "id": "def2c3c0-699b-431b-a370-12798f07a999"
            }
          ]
        },
        {
          "id": "b2de3319-0cec-44bf-8092-6efa5056652c",
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
              "id": "112eec23-610d-4c20-b722-80a983f78055"
            }
          ]
        }
      ]
    },
    {
      "name": "Supplier",
      "item": [
        {
          "id": "c3bdebca-badd-4c14-94a7-3b0c18c4228c",
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
              "id": "12142682-0168-400e-ab5e-0f61f770bf72"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "78dc4c36-75a5-4f38-9320-a06d17d8e7d3",
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
              "id": "3a6d5b5a-c260-4e1d-8fca-772e28fd0c0f"
            }
          ]
        }
      ]
    }
  ]
}