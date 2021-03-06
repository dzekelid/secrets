---
swagger: "2.0"
x-collection-name: Paylocity
x-complete: 0
info:
  title: Paylocity Obtain new client secret.
  description: Obtain new client secret for Paylocity-issued client id. See Setup
    section for details.
  termsOfService: WebLink.OpenApiDoc.TermsOfService
  version: "2"
host: api.paylocity.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/credentials/secrets:
    post:
      summary: Obtain new client secret.
      description: Obtain new client secret for Paylocity-issued client id. See Setup
        section for details.
      operationId: v2.credentials.secrets.post
      x-api-path-slug: v2credentialssecrets-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer + JWT
      - in: body
        name: json
        description: Add Client Secret Model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - V2
      - Credentials
      - Secrets
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