---
name: Blizzard
x-slug: blizzard
description: This is the documentation for the RESTful APIs exposed through the World
  of Warcraft community site as a service to the World of Warcraft community.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Data
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/apis.md
specificationVersion: "0.14"
apis:
- name: World of Warcraft Get Auction Data Realm
  x-api-slug: world-of-warcraft
  description: Provides a per-realm list of recently generated auction house data
    dumps. The current auctions data is represented as JSON structures containing
    auction data for the tree auctions houses available on each realm.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow///auction/data/{realm}
  tags: Auction,Data,Realm
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/auctiondatarealm-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/auctiondatarealm-get-openapi.md
- name: World of Warcraft Get Data Character Races
  x-api-slug: world-of-warcraft
  description: Provides a list of character races.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow///data/character/races
  tags: Data,Character,Races
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/datacharacterraces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/datacharacterraces-get-openapi.md
- name: World of Warcraft Get Data Character Classes
  x-api-slug: world-of-warcraft
  description: Provides a list of character classes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow///data/character/classes
  tags: Data,Character,Classes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/datacharacterclasses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/datacharacterclasses-get-openapi.md
- name: World of Warcraft Get Data Guild Rewards
  x-api-slug: world-of-warcraft
  description: Provides a list of all guild rewards.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow///data/guild/rewards
  tags: Data,Guild,Rewards
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/dataguildrewards-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/dataguildrewards-get-openapi.md
- name: World of Warcraft Get Data Guild Perks
  x-api-slug: world-of-warcraft
  description: Provides a list of all guild perks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow///data/guild/perks
  tags: Data,Guild,Perks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/dataguildperks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/dataguildperks-get-openapi.md
- name: World of Warcraft Get Data Item Classes
  x-api-slug: world-of-warcraft
  description: Provides a list of item classes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow///data/item/classes
  tags: Data,Item,Classes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/dataitemclasses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/dataitemclasses-get-openapi.md
- name: World of Warcraft
  x-api-slug: world-of-warcraft
  description: Battle.net is a site that aims to unite all Blizzard gamers under the
    banner of a single, powerful, and advanced online gaming service. Gamers around
    the world meet up on Battle.net to prove their skill in multiplayer matches or
    to socialize with their friends. The World of Warcraft specific APIs are available
    to the Battle.net community, developers and partners to help expose some of the
    sought after data already served by the World of Warcraft community site. Currently
    data exposed includes realm status with  character, guild and arena team profile
    pages information to come later. The API uses RESTful calls and responses are
    formatted in JSON and JSONP.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/blizzard/openapi.md
x-common:
- type: x-api-json--authoritative
  url: http://apis.io/apisdef/legacy/blizzard.json
- type: x-developer
  url: https://dev.battle.net/
- type: x-github
  url: https://github.com/Blizzard
- type: x-twitter
  url: Blizzard_Ent
- type: x-website
  url: http://battle.net
- type: x-website
  url: https://www.blizzard.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---