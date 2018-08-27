---
swagger: "2.0"
x-collection-name: Click Meter
x-complete: 0
info:
  title: Click Meter Delete an ip blacklist entry
  description: Delete an ip blacklist entry.
  contact:
    name: Api Support
    url: http://www.clickmeter.com/api
    email: api@clickmeter.com
  version: v2
host: apiv2.clickmeter.com:80
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/ipblacklist/{blacklistId}:
    delete:
      summary: Delete an ip blacklist entry
      description: Delete an ip blacklist entry.
      operationId: deleteAccountIpblacklistBlacklist
      x-api-path-slug: accountipblacklistblacklistid-delete
      parameters:
      - in: path
        name: blacklistId
        description: The id of the ip to delete
      responses:
        200:
          description: OK
      tags:
      - Account
      - Ipblacklist
      - BlacklistId
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