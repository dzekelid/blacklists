{
  "info": {
    "name": "Auth0 Blacklists API Get Blacklists Tokens",
    "_postman_id": "bb93244d-da05-4902-a0d9-7797a374534b",
    "description": "Get blacklists tokens.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Blacklists",
      "item": [
        {
          "id": "5f84a846-3194-42d8-ac5e-935b7195935a",
          "name": "get_tokens",
          "request": {
            "url": "http://login.auth0.com/blacklists/api/v2/blacklists/tokens?aud=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get blacklists tokens."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cf3f7a1-16b2-4169-8f92-c29eabc20b9e"
            }
          ]
        }
      ]
    }
  ]
}