{
  "info": {
    "name": "World of Warcraft Get Data Character Classes",
    "_postman_id": "32dc4ba6-1c3c-435a-8fff-1f9ca1f3f85f",
    "description": "Provides a list of character classes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Data",
      "item": [
        {
          "id": "d3d3a115-6cba-41c5-9fe2-908b1d4112d5",
          "name": "getDataCharacterClasses",
          "request": {
            "url": "http://us.battle.net/api/wow/data/character/classes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides a list of character classes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c3be18b-13ea-4c53-a6b0-34eecc210d7f"
            }
          ]
        }
      ]
    }
  ]
}