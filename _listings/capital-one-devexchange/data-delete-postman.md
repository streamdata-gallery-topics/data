{
  "info": {
    "name": "Capital One DevExchange Delete data associated with your API key.",
    "_postman_id": "cfc8609a-c113-48b5-966c-49d402f27ef6",
    "description": "This endpoint deletes any data associated with your API key and of the type passed in as query parameters.  If you do not specify any type to delete, no data will be deleted.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "b8f7ae09-fd4f-4a89-8665-f07a76302e0d",
          "name": "this-endpoint-deletes-any-data-associated-with-your-api-key-and-of-the-type-passed-in-as-query-param",
          "request": {
            "url": "http://api.reimaginebanking.com/data?type=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint deletes any data associated with your API key and of the type passed in as query parameters"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8663b091-76a3-429e-b6c8-6141eeb1fd38"
            }
          ]
        }
      ]
    }
  ]
}