---
swagger: "2.0"
x-collection-name: BigStickCarpet
x-complete: 1
info:
  title: Stack API
  description: todo-add-description
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
  /push:
    post:
      summary: Push invalid values into stack
      description: Add values into the stack
      operationId: PushPost2
      x-api-path-slug: push-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: header
        name: x-mock-response-code
      responses:
        200:
          description: OK
      tags:
      - ""
---