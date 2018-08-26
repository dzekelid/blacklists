{
  "info": {
    "name": "Auth0 API Get Blacklists Tokens",
    "_postman_id": "a7224e24-ca2d-4ccd-b5e9-35304cc281b1",
    "description": "Get blacklists tokens.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Blacklists",
      "item": [
        {
          "id": "bef0f6db-e4c3-43a3-be5f-b70d6690ce0f",
          "name": "getBlacklistsTokens",
          "request": {
            "url": "http://login.auth0.com/api/v2/blacklists/tokens?aud=%7B%7D",
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
              "id": "38756a57-e9b1-44ea-8e03-5433f526464e"
            }
          ]
        }
      ]
    }
  ]
}