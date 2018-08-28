swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/mfa/generate:
    post:
      summary: Generate MFA secret
      description: |-
        Generates an multi-factor authentication secret for a user and returns it as a string and as base64 encoded QR code image.
        ##### Permissions
        Must be logged in as the user or have the `edit_other_users` permission.
      operationId: generates-an-multifactor-authentication-secret-for-a-user-and-returns-it-as-a-string-and-as-base64-e
      x-api-path-slug: usersuser-idmfagenerate-post
      parameters:
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Generate
      - MFA
      - Secret
  /oauth/apps/{app_id}/regen_secret:
    post:
      summary: Regenerate OAuth app secret
      description: |-
        Regenerate the client secret for an OAuth 2.0 client application registered with Mattermost.
        ##### Permissions
        If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
      operationId: regenerate-the-client-secret-for-an-oauth-20-client-application-registered-with-mattermost-permissio
      x-api-path-slug: oauthappsapp-idregen-secret-post
      parameters:
      - in: path
        name: app_id
        description: Application client id
      responses:
        200:
          description: OK
      tags:
      - Regenerate
      - OAuth
      - App
      - Secret