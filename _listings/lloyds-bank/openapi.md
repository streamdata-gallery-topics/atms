swagger: "2.0"
x-collection-name: Lloyds Bank
x-complete: 1
info:
  title: Lloyds Bank
  description: this-is-an-openapi-definition-for-the-standard-set-of-open-banking-httpopenbankingapis-io-apis-from-lloyds-ban-
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: api.lloydsbank.com
basePath: open-banking/v2.1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  atms/:
    get:
      summary: Get ATMs
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can provide multiple ATMs.
      operationId: getATMS
      x-api-path-slug: atms-get
      responses:
        200:
          description: OK
      tags:
      - Atms