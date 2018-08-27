---
swagger: "2.0"
x-collection-name: BigCommerce
x-complete: 1
info:
  title: BigCommerce API V3
  description: collection-of-requests-for-interacting-with-bigcommerces-v3-api
  version: 1.0.0
host: api.bigcommerce.com
basePath: /stores
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{store-hash}/v3/catalog/products/{id}/images/{id}:
    get:
      summary: Retrieve a single product image's data
      description: GET request for a specific product image by ID
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsidimagesid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Single
      - Product
      - Images
      - Data
---