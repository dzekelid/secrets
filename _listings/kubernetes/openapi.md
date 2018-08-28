swagger: "2.0"
x-collection-name: Kubernetes
x-complete: 1
info:
  title: Kubernetes
  version: 1.0.0
host: /api/v1beta3
basePath: 127.0.0.1:6443
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1beta3/namespaces/{namespaces}/secrets:
    get:
      summary: Get Namespaces Secrets
      description: List objects of kind secret.
      operationId: listSecret
      x-api-path-slug: apiv1beta3namespacesnamespacessecrets-get
      parameters:
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Secrets
    post:
      summary: Post Namespaces Secrets
      description: Create a secret.
      operationId: createSecret
      x-api-path-slug: apiv1beta3namespacesnamespacessecrets-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Secrets
  /api/v1beta3/namespaces/{namespaces}/secrets/{name}:
    delete:
      summary: Delete Namespaces Secrets Name
      description: Delete a secret.
      operationId: deleteSecret
      x-api-path-slug: apiv1beta3namespacesnamespacessecretsname-delete
      parameters:
      - in: path
        name: name
        description: name of the Secret
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Secrets
      - Name
    get:
      summary: Get Namespaces Secrets Name
      description: Read the specified secret.
      operationId: readSecret
      x-api-path-slug: apiv1beta3namespacesnamespacessecretsname-get
      parameters:
      - in: path
        name: name
        description: name of the Secret
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Secrets
      - Name
    put:
      summary: Put Namespaces Secrets Name
      description: Update the specified secret.
      operationId: updateSecret
      x-api-path-slug: apiv1beta3namespacesnamespacessecretsname-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: name of the Secret
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Secrets
      - Name
  /api/v1beta3/secrets:
    get:
      summary: Get Secrets
      description: List objects of kind secret.
      operationId: listSecret
      x-api-path-slug: apiv1beta3secrets-get
      responses:
        200:
          description: OK
      tags:
      - Secrets
  /api/v1beta3/watch/namespaces/{namespaces}/secrets:
    get:
      summary: Get Watch Namespaces Secrets
      description: Watch a list of secret.
      operationId: watchSecretlist
      x-api-path-slug: apiv1beta3watchnamespacesnamespacessecrets-get
      parameters:
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Watch
      - Namespaces
      - Secrets
  /api/v1beta3/watch/namespaces/{namespaces}/secrets/{name}:
    get:
      summary: Get Watch Namespaces Secrets Name
      description: Watch a particular secret.
      operationId: watchSecret
      x-api-path-slug: apiv1beta3watchnamespacesnamespacessecretsname-get
      parameters:
      - in: path
        name: name
        description: name of the Secret
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Watch
      - Namespaces
      - Secrets
      - Name
  /api/v1beta3/watch/secrets:
    get:
      summary: Get Watch Secrets
      description: Watch a list of secret.
      operationId: watchSecretlist
      x-api-path-slug: apiv1beta3watchsecrets-get
      responses:
        200:
          description: OK
      tags:
      - Watch
      - Secrets