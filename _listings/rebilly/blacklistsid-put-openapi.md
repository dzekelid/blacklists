---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Create a blacklist with predefined ID
  description: Create a blacklist with predefined identifier string
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /blacklists:
    get:
      summary: Retrieve a list of blacklists
      description: Retrieve a list of blacklists
      operationId: blacklists.get
      x-api-path-slug: blacklists-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Blacklists
    post:
      summary: Create a blacklist
      description: Create a blacklist
      operationId: blacklists.post
      x-api-path-slug: blacklists-post
      parameters:
      - in: body
        name: body
        description: Blacklist resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Blacklist
  /blacklists/{id}:
    delete:
      summary: Delete a blacklist
      description: Delete a blacklist with predefined identifier string
      operationId: blacklists.id.delete
      x-api-path-slug: blacklistsid-delete
      responses:
        200:
          description: OK
      tags:
      - Blacklist
    get:
      summary: Retrieve a blacklist
      description: Retrieve a blacklist with specified identifier string
      operationId: blacklists.id.get
      x-api-path-slug: blacklistsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Blacklist
    put:
      summary: Create a blacklist with predefined ID
      description: Create a blacklist with predefined identifier string
      operationId: blacklists.id.put
      x-api-path-slug: blacklistsid-put
      parameters:
      - in: body
        name: body
        description: Blacklist resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Blacklist
      - Predefined
      - ID
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