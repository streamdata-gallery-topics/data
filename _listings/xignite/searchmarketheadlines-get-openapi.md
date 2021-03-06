---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Releases Search Market Headlines
  description: Search market headlines across all companies based on date, source,
    and title.
  version: v1
host: http://www.xignite.com/
basePath: xReleases.xml/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  GetHistoricalMarketHeadlines/:
    get:
      summary: Get Historical Market Headlines
      description: Returns market headlines for a date range.
      operationId: getGethistoricalmarketheadlines
      x-api-path-slug: gethistoricalmarketheadlines-get
      parameters:
      - in: query
        name: EndDate
        description: The end date range
      - in: query
        name: Source
        description: The source of the news
      - in: query
        name: StartDate
        description: The start date range
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Market
      - Headlines
  GetHistoricalSecurityHeadlines/:
    get:
      summary: Get Historical Security Headlines
      description: Returns headlines for a company and a date range.
      operationId: getGethistoricalsecurityheadlines
      x-api-path-slug: gethistoricalsecurityheadlines-get
      parameters:
      - in: query
        name: EndDate
        description: EndDate
      - in: query
        name: Identifier
        description: The ticker symbol for company
      - in: query
        name: IdentifierType
        description: The identifier to use
      - in: query
        name: Source
        description: The source of the news
      - in: query
        name: StartDate
        description: The start date range
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Security
      - Headlines
  GetLastMarketHeadlines/:
    get:
      summary: Get Last Market Headlines
      description: Returns market headlines published since a specific date and time.
      operationId: getGetlastmarketheadlines
      x-api-path-slug: getlastmarketheadlines-get
      parameters:
      - in: query
        name: SinceDate
        description: The beginning of data range
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Last
      - Market
      - Headlines
  GetLastSecurityHeadlines/:
    get:
      summary: Get Last Security Headlines
      description: Returns headlines for a company published since a specific date
        and time.
      operationId: getGetlastsecurityheadlines
      x-api-path-slug: getlastsecurityheadlines-get
      parameters:
      - in: query
        name: Identifier
        description: The ticker symbol for company
      - in: query
        name: IdentifierType
        description: The identifier to use
      - in: query
        name: SinceDate
        description: The start date range
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Last
      - Security
      - Headlines
  GetReleaseContent/:
    get:
      summary: Get Release Content
      description: Return detailed information about a release as well as its content.
      operationId: getGetreleasecontent
      x-api-path-slug: getreleasecontent-get
      parameters:
      - in: query
        name: ReleaseID
        description: The press release ID>
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Release
      - Content
  GetTodaysSecurityHeadlines:
    get:
      summary: Get Todays Security Headlines
      description: Returns headlines for a company published today.
      operationId: getGettodayssecurityheadlines
      x-api-path-slug: gettodayssecurityheadlines-get
      parameters:
      - in: query
        name: Identifier
        description: The ticker symbol for company
      - in: query
        name: IdentifierType
        description: The identifier to use
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Todays
      - Security
      - Headlines
  GetTopMarketHeadlines/:
    get:
      summary: Get Top Market Headlines
      description: Returns a given number of market headlines published most recently.
      operationId: getGettopmarketheadlines
      x-api-path-slug: gettopmarketheadlines-get
      parameters:
      - in: query
        name: Count
        description: The number of news items to return
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Top
      - Market
      - Headlines
  GetTopSecurityHeadlines/:
    get:
      summary: Get Top Security Headlines
      description: Returns a given number of company headlines published most recently.
      operationId: getGettopsecurityheadlines
      x-api-path-slug: gettopsecurityheadlines-get
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Top
      - Security
      - Headlines
  SearchMarketHeadlines/:
    get:
      summary: Search Market Headlines
      description: Search market headlines across all companies based on date, source,
        and title.
      operationId: getSearchmarketheadlines
      x-api-path-slug: searchmarketheadlines-get
      parameters:
      - in: query
        name: EndDate
        description: The end date range
      - in: query
        name: Source
        description: The source of the news
      - in: query
        name: StartDate
        description: The start date range
      - in: query
        name: Title
        description: Title of the headlines
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Search
      - Market
      - Headlines
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