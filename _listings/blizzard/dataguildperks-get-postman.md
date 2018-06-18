{
  "info": {
    "name": "World of Warcraft Get Data Guild Perks",
    "_postman_id": "4cd5662c-df8b-497e-8bc6-9e31e6edb75f",
    "description": "Provides a list of all guild perks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Auction",
      "item": [
        {
          "id": "3ae82eec-ac48-49cb-885a-d5ca2a41fb3a",
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
              "id": "f71983a7-9711-4168-81a5-a558926c43ba"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "5f00f492-7bb3-4f16-89bc-574a9e7d7dba",
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
              "id": "735e16c8-7eee-41bb-9dba-bfb9dc0eede6"
            }
          ]
        },
        {
          "id": "db87c193-e8e5-4adb-ae46-516a319135ad",
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
              "id": "110675d5-b319-4d5f-8d95-cb18519ec6db"
            }
          ]
        },
        {
          "id": "d834cc7c-ba37-46d0-9cab-7a02584525b8",
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
              "id": "5cfcf397-21a8-41a3-8e2f-475374f7a565"
            }
          ]
        },
        {
          "id": "9dbf958e-3d24-4733-8b6d-8af920314747",
          "name": "getDataGuildPerks",
          "request": {
            "url": "http://us.battle.net/api/wow/data/guild/perks",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides a list of all guild perks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "591cd127-6e28-44ab-b48a-72b07c324f8c"
            }
          ]
        }
      ]
    }
  ]
}