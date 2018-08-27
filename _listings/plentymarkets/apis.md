---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Data
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - Find address data by address id
  x-api-slug: restaccountsaddressesaddressidrelated-data-get
  description: Find address data by address id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restaccountsaddressesaddressidrelated-data-get-openapi.md
- name: plentymarkets REST-API - List all group function related data
  x-api-slug: restaccountscontactsgroup-functions-get
  description: Lists all data that is related to the contact group function contents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restaccountscontactsgroup-functions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restaccountscontactsgroup-functions-get-openapi.md
- name: plentymarkets REST-API - Return all contact related data
  x-api-slug: restaccountscontactscontactidrelated-data-get
  description: Returns all contact related data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restaccountscontactscontactidrelated-data-get-openapi.md
- name: plentymarkets REST-API - Update sales price data
  x-api-slug: restitemsidvariationsvariationidvariation-sales-pricespriceid-put
  description: Updates sales price data linked to a variation. The ID of the sales
    price and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-pricespriceid-put-openapi.md
- name: plentymarkets REST-API - Update warehouse data of a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-put
  description: Updates the data of a warehouse linked to a variation. The ID of the
    variation and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-put-openapi.md
- name: plentymarkets REST-API - Update additional data of the shipping information
  x-api-slug: restordersorderidshippingshipping-informationadditional-data-put
  description: Updates additional data of the shipping information. The ID of the
    order must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restordersorderidshippingshipping-informationadditional-data-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restordersorderidshippingshipping-informationadditional-data-put-openapi.md
- name: plentymarkets REST-API - Get sales price data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-sales-pricespriceid-get
  description: Gets sales price data linked to a variation. The ID of the sales price
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-pricespriceid-get-openapi.md
- name: plentymarkets REST-API - Get supplier data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get
  description: Gets the data for a supplier linked to a variation. The ID of the variation
    and the ID of the link between the variation and the supplier must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get-openapi.md
- name: plentymarkets REST-API - Updates supplier data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put
  description: Updates the data of a supplier linked to a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put-openapi.md
- name: plentymarkets REST-API - Get warehouse data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-get
  description: Gets the data of a warehouse linked to a variation. The ID of the variation
    and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-openapi.md
- name: plentymarkets REST-API - Get sales price data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-sales-pricespriceid-get
  description: Gets sales price data linked to a variation. The ID of the sales price
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-pricespriceid-get-openapi.md
- name: plentymarkets REST-API - Get supplier data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get
  description: Gets the data for a supplier linked to a variation. The ID of the variation
    and the ID of the link between the variation and the supplier must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get-openapi.md
- name: plentymarkets REST-API - Updates supplier data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put
  description: Updates the data of a supplier linked to a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put-openapi.md
- name: plentymarkets REST-API - Get warehouse data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-get
  description: Gets the data of a warehouse linked to a variation. The ID of the variation
    and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-openapi.md
- name: plentymarkets REST-API - Get warehouse data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-warehouseswarehouseid-get
  description: Gets the data of a warehouse linked to a variation. The ID of the variation
    and the ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-warehouseswarehouseid-get-openapi.md
- name: plentymarkets REST-API - Updates supplier data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put
  description: Updates the data of a supplier linked to a variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-put-openapi.md
- name: plentymarkets REST-API - Get supplier data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get
  description: Gets the data for a supplier linked to a variation. The ID of the variation
    and the ID of the link between the variation and the supplier must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-suppliersvariationsupplierid-get-openapi.md
- name: plentymarkets REST-API - Get sales price data for a variation
  x-api-slug: restitemsidvariationsvariationidvariation-sales-pricespriceid-get
  description: Gets sales price data linked to a variation. The ID of the sales price
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/plentymarkets/restitemsidvariationsvariationidvariation-sales-pricespriceid-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---