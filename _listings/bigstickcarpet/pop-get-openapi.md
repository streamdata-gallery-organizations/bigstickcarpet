---
swagger: "2.0"
x-collection-name: BigStickCarpet
x-complete: 0
info:
  title: bigstickcarpet.com Pop empty stack
  description: Get a value from the stack
  version: "1.0"
host: bigstickcarpet.com
basePath: /postman-bdd/dist
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /postman-bdd.min.js:
    get:
      summary: Install Postman BDD
      description: ""
      operationId: PostmanBddMinJsGet
      x-api-path-slug: postmanbdd-min-js-get
      responses:
        200:
          description: OK
      tags:
      - ""
  /pop:
    get:
      summary: Pop empty stack
      description: Get a value from the stack
      operationId: PopGet2
      x-api-path-slug: pop-get
      parameters:
      - in: header
        name: x-mock-response-code
      responses:
        200:
          description: OK
      tags:
      - ""
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