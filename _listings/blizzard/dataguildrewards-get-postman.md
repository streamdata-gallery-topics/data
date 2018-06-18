{
  "info": {
    "name": "World of Warcraft Get Data Guild Rewards",
    "_postman_id": "c5095a27-2f06-4cbc-8c53-62fac9221e98",
    "description": "Provides a list of all guild rewards.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Auction",
      "item": [
        {
          "id": "30cab023-07c0-476d-874a-668468f34af5",
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
              "id": "375a7858-b7cb-4ccf-b38b-3e68807e8f32"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "62d9af34-19e8-4de5-a5f4-75d1adf33cff",
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
              "id": "139c9493-1240-442f-932c-190fde0ae326"
            }
          ]
        },
        {
          "id": "76486330-009f-4e06-9484-560eea4c64eb",
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
              "id": "5d0f78b0-5630-41a4-980a-708e45959cd7"
            }
          ]
        },
        {
          "id": "37b97477-750f-4801-a161-4af64f15b9b6",
          "name": "getDataGuildRewards",
          "request": {
            "url": "http://us.battle.net/api/wow/data/guild/rewards",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides a list of all guild rewards."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ce0131c-d47b-4959-bcf4-f8d273bb36da"
            }
          ]
        }
      ]
    }
  ]
}