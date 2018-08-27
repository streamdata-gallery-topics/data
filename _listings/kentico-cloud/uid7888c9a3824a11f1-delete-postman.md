{
  "info": {
    "name": "Kentico Cloud Delete data of visitor by ID",
    "_postman_id": "dd38283f-a1ae-4adc-9236-fa8c1ac2516a",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "7cea2170-e418-47a8-be18-5194e9a22cbc",
          "name": "Segment569030c752a544f5A243C5285b3eb24eVisitorsBySegmentNameGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "deliver.kenticocloud.com",
              "path": [
                "segment/569030c7-52a5-44f5-a243-c5285b3eb24e/:SegmentName/visitors"
              ],
              "variable": [
                {
                  "id": "SegmentName",
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
            "description": "Retrieve visitors that match the specified segment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44cf3745-fdd4-4a9c-af05-129dc458768e"
            }
          ]
        },
        {
          "id": "aab61df2-93ac-4ee7-9c65-ba499ec5d54e",
          "name": "Visitor569030c752a544f5A243C5285b3eb24e7888c9a3824a11f1SegmentsGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/visitor/569030c7-52a5-44f5-a243-c5285b3eb24e/7888c9a3824a11f1/segments",
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
            "description": "Retrieve the names of segments that the specified visitor belongs to."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90ebf216-557d-43be-a243-ad6d900d3247"
            }
          ]
        }
      ]
    },
    {
      "name": "Retrieving",
      "item": [
        {
          "id": "ea9dfe7d-9c65-45fc-9ac3-4626a66ea5c4",
          "name": "Visitor569030c752a544f5A243C5285b3eb24eE3e9e191a12b9257SegmentGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/visitor/569030c7-52a5-44f5-a243-c5285b3eb24e/e3e9e191a12b9257/segment",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Use the Personalization API to retrieve the list of segments that the specified visitor belongs to.\n\n* Authenticate the request using your Personalization API Key.\n* Specify the User ID of the visitor you are asking about.\n \nSee <https://developer.kenticocloud.com/docs/personalizing-content#section-retrieving-visitor-s-segments> for more details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "55a2c442-7d43-47e0-92be-62ae570ee34d"
            }
          ]
        }
      ]
    },
    {
      "name": "View",
      "item": [
        {
          "id": "6501c21e-38b8-4dd3-82b7-d1afd986abc5",
          "name": "Uid7888c9a3824a11f1Get",
          "request": {
            "url": "http://deliver.kenticocloud.com/uid/7888c9a3824a11f1",
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
            "description": "View data of visitor by ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60cfba31-9463-4f9d-b2ac-cb5e1c4024c0"
            }
          ]
        },
        {
          "id": "a798b856-cf21-4028-9238-06cb0bdbe9fa",
          "name": "EmailLolaMiraBlablaComGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/email/lola.mira@blabla.com",
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
            "description": "View data of visitor by email"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a4e6463-f5fd-4eb0-9375-bb8d1f119e00"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "e6c136c4-bd13-4fb0-8647-967d3f6b67d2",
          "name": "Uid7888c9a3824a11f1Delete",
          "request": {
            "url": "http://deliver.kenticocloud.com/uid/7888c9a3824a11f1",
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
            "description": "Delete data of visitor by ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3189e6db-9b88-4546-bd0a-32f1393647c6"
            }
          ]
        },
        {
          "id": "f93399e4-1c80-4a75-8c53-b0b26b4851c7",
          "name": "EmailLolaMiraBlablaComDelete",
          "request": {
            "url": "http://deliver.kenticocloud.com/email/lola.mira@blabla.com",
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
            "description": "Delete data of visitor by email"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b33f71f8-66d0-45f4-81c2-c934bfcf5d6c"
            }
          ]
        }
      ]
    }
  ]
}