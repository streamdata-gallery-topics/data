swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 1
info:
  title: Capital One DevExchange
  description: nessie-is-capital-ones-hackathon-api-that-gives-you-access-to-a-multitude-of-real-publicfacing-data--such-as-atm-and-bank-branch-locations--along-with-mock-customer-account-data--use-http-requests-to-set-up-peertopeer-transactions-simulate-a-weekly-paycheck-or-even-schedule-bills-for-customers-this-is-all-structured-in-a-way-that-resembles-how-we-actually-run-things-here-at-capital-one-
  version: 1.0.0
host: api.reimaginebanking.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /data:
    delete:
      summary: Delete data associated with your API key.
      description: This endpoint deletes any data associated with your API key and
        of the type passed in as query parameters.  If you do not specify any type
        to delete, no data will be deleted.
      operationId: this-endpoint-deletes-any-data-associated-with-your-api-key-and-of-the-type-passed-in-as-query-param
      x-api-path-slug: data-delete
      parameters:
      - in: query
        name: type
        description: Collection to delete data from
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Data