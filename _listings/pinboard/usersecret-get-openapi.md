---
swagger: "2.0"
x-collection-name: Pinboard
x-complete: 0
info:
  title: Pinboard Get User Secret
  description: Get the secret RSS token (allows viewing user's private RSS feeds).
  version: 1.0.0
host: api.pinboard.in
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/secret:
    get:
      summary: Get User Secret
      description: Get the secret RSS token (allows viewing user's private RSS feeds).
      operationId: user.secret.get
      x-api-path-slug: usersecret-get
      responses:
        200:
          description: OK
      tags:
      - User
      - Secret
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