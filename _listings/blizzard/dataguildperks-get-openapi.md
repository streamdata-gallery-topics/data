---
swagger: "2.0"
x-collection-name: Blizzard
x-complete: 0
info:
  title: World of Warcraft Get Data Guild Perks
  description: Provides a list of all guild perks.
  version: 1.0.0
host: us.battle.net
basePath: /api/wow/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /auction/data/{realm}:
    get:
      summary: Get Auction Data Realm
      description: Provides a per-realm list of recently generated auction house data
        dumps. The current auctions data is represented as JSON structures containing
        auction data for the tree auctions houses available on each realm.
      operationId: getAuctionDataRealm
      x-api-path-slug: auctiondatarealm-get
      parameters:
      - in: path
        name: realm
        description: The realm name
      responses:
        200:
          description: OK
      tags:
      - Auction
      - Data
      - Realm
  /data/character/races:
    get:
      summary: Get Data Character Races
      description: Provides a list of character races.
      operationId: getDataCharacterRaces
      x-api-path-slug: datacharacterraces-get
      responses:
        200:
          description: OK
      tags:
      - Data
      - Character
      - Races
  /data/character/classes:
    get:
      summary: Get Data Character Classes
      description: Provides a list of character classes.
      operationId: getDataCharacterClasses
      x-api-path-slug: datacharacterclasses-get
      responses:
        200:
          description: OK
      tags:
      - Data
      - Character
      - Classes
  /data/guild/rewards:
    get:
      summary: Get Data Guild Rewards
      description: Provides a list of all guild rewards.
      operationId: getDataGuildRewards
      x-api-path-slug: dataguildrewards-get
      responses:
        200:
          description: OK
      tags:
      - Data
      - Guild
      - Rewards
  /data/guild/perks:
    get:
      summary: Get Data Guild Perks
      description: Provides a list of all guild perks.
      operationId: getDataGuildPerks
      x-api-path-slug: dataguildperks-get
      responses:
        200:
          description: OK
      tags:
      - Data
      - Guild
      - Perks
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---