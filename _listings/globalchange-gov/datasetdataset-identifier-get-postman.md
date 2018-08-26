{
  "info": {
    "name": "Global Change Information System API Get a representation of a dataset.",
    "_postman_id": "66a15afa-1933-4095-9969-d7603ffcb366",
    "description": "Get JSON which represents the structure of a dataset.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Datasets",
      "item": [
        {
          "id": "d552263f-96ca-4211-9f21-06d0c664fe69",
          "name": "list-the-datasets-20-per-page",
          "request": {
            "url": "http://data.globalchange.gov/dataset?all=%7B%7D&page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the datasets, 20 per page."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1ba8ded-4429-4dfa-a812-c8f35810d85b"
            }
          ]
        }
      ]
    },
    {
      "name": "Look",
      "item": [
        {
          "id": "080e0d77-d393-46f0-bd9b-2964901e1dec",
          "name": "given-a-doi-return-a-redirect-to-the-gcis-dataset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "dataset/lookup/:doi"
              ],
              "variable": [
                {
                  "id": "doi",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a DOI, return a redirect to the GCIS dataset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b14279c9-72b3-47e1-b421-50c43470d482"
            }
          ]
        }
      ]
    },
    {
      "name": "Representation",
      "item": [
        {
          "id": "41a76377-0702-4be4-8df0-c11a7fb9fa9a",
          "name": "get-json-which-represents-the-structure-of-a-dataset",
          "request": {
            "url": {
              "protocol": "http",
              "host": "data.globalchange.gov",
              "path": [
                "dataset/:dataset_identifier"
              ],
              "variable": [
                {
                  "id": "dataset_identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get JSON which represents the structure of a dataset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "596d12e7-39d3-447d-8815-9f3efb4e0971"
            }
          ]
        }
      ]
    }
  ]
}