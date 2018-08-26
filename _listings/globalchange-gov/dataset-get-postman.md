{
  "info": {
    "name": "Global Change Information System API List datasets.",
    "_postman_id": "53e8d958-cb48-445f-b644-3e84f5993ee6",
    "description": "List the datasets, 20 per page.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Datasets",
      "item": [
        {
          "id": "b0065367-f3c5-4f0d-b5fe-fb51cd98ce19",
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
              "id": "69d5b8d9-aeae-49c7-a44f-cfd6cef71034"
            }
          ]
        }
      ]
    }
  ]
}