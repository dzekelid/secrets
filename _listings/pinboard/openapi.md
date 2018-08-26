---
swagger: "2.0"
x-collection-name: Pinboard
x-complete: 1
info:
  title: Pinboard
  description: store-manage-and-share-bookmarks-on-pinboard
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
---