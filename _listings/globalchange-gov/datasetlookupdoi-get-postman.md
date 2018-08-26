{
  "info": {
    "name": "Global Change Information System API Look up a dataset by DOI.",
    "_postman_id": "9ef26d1d-eab5-496a-9769-824dcfaa35c0",
    "description": "Given a DOI, return a redirect to the GCIS dataset.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Datasets",
      "item": [
        {
          "id": "c07bb81e-507c-4f2d-aba6-fb480ca377f5",
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
              "id": "32bbed98-2eac-478c-9a20-cdad16a77bf7"
            }
          ]
        }
      ]
    },
    {
      "name": "Look",
      "item": [
        {
          "id": "a072c177-933c-49d1-a8ac-d0dcc7b6c6d3",
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
              "id": "8056daec-bba6-4ff7-bada-02b97078eac9"
            }
          ]
        }
      ]
    }
  ]
}