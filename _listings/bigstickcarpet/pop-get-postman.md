{
  "info": {
    "name": "bigstickcarpet.com Pop empty stack",
    "_postman_id": "62ea5870-c3cd-42d1-b5da-046a65411a0a",
    "description": "Get a value from the stack",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "0cf2b9e2-d64d-4e19-98ed-040ae97c0d46",
      "name": "PostmanBddMinJsGet",
      "request": {
        "url": "http://bigstickcarpet.com/postman-bdd/dist/postman-bdd.min.js",
        "method": "GET",
        "header": [
          {
            "key": "Accept",
            "value": "*/*",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Install Postman BDD"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ae650997-002f-4b08-ae29-da9849e95b96"
        }
      ]
    },
    {
      "id": "40d47475-1aeb-4adf-a25a-efe35f518202",
      "name": "PopGet2",
      "request": {
        "url": "http://bigstickcarpet.com/postman-bdd/dist/pop",
        "method": "GET",
        "header": [
          {
            "key": "x-mock-response-code",
            "value": "{}",
            "description": "",
            "disabled": false
          },
          {
            "key": "Accept",
            "value": "*/*",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Get a value from the stack"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "af113066-70ae-4f2d-b96b-0c4f9c747d1e"
        }
      ]
    }
  ]
}