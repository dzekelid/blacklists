---
swagger: "2.0"
x-collection-name: Auth0
x-complete: 0
info:
  title: Auth0 Blacklists API Get Blacklists Tokens
  version: v1
  description: Get blacklists tokens.
host: login.auth0.com
basePath: /blacklists
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v2/blacklists/tokens:
    get:
      summary: Get Blacklists Tokens
      description: Get blacklists tokens.
      operationId: get_tokens
      x-api-path-slug: apiv2blackliststokens-get
      parameters:
      - in: query
        name: aud
        description: The JWTs aud claim
      responses:
        200:
          description: OK
      tags:
      - Blacklists
      - Tokens
    post:
      summary: Post Blacklists Tokens
      description: Post blacklists tokens.
      operationId: post_tokens
      x-api-path-slug: apiv2blackliststokens-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Blacklists
      - Tokens
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