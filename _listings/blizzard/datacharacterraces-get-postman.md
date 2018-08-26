{
  "info": {
    "name": "World of Warcraft Get Data Character Races",
    "_postman_id": "b21ee3c6-6354-4613-9ceb-9a3e7e6281a5",
    "description": "Provides a list of character races.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Auction",
      "item": [
        {
          "id": "f63deb29-efc7-474f-8e33-88767e5e0e89",
          "name": "getAuctionDataRealm",
          "request": {
            "url": {
              "protocol": "http",
              "host": "us.battle.net",
              "path": [
                "api",
                "wow",
                "auction/data/:realm"
              ],
              "variable": [
                {
                  "id": "realm",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides a per-realm list of recently generated auction house data dumps. The current auctions data is represented as JSON structures containing auction data for the tree auctions houses available on each realm."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21422978-6eff-448d-9912-2b72cae7c543"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "e6323998-d12b-40ed-b8b8-2bfa5c98df16",
          "name": "getDataCharacterRaces",
          "request": {
            "url": "http://us.battle.net/api/wow/data/character/races",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides a list of character races."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce93aa9b-55c0-4f1e-814f-f30d6e390b8b"
            }
          ]
        }
      ]
    }
  ]
}