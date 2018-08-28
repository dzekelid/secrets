---
name: Kubernetes
x-slug: kubernetes
description: Manage a cluster of Linux containers as a single system to accelerate
  Dev and simplify Ops. Kubernetes is an open source orchestration system for Docker
  containers. It handles scheduling onto nodes in a compute cluster and actively manages
  workloads to ensure that their state matches the users declared intentions. Using
  the concepts of labels and pods, it groups the containers which make up an application
  into logical units for easy management and discovery.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Secrets
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apis.md
specificationVersion: "0.14"
apis:
- name: Kubernetes - Get Namespaces Secrets
  x-api-slug: apiv1beta3namespacesnamespacessecrets-get
  description: List objects of kind secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecrets-get-openapi.md
- name: Kubernetes - Post Namespaces Secrets
  x-api-slug: apiv1beta3namespacesnamespacessecrets-post
  description: Create a secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecrets-post-openapi.md
- name: Kubernetes - Delete Namespaces Secrets Name
  x-api-slug: apiv1beta3namespacesnamespacessecretsname-delete
  description: Delete a secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecretsname-delete-openapi.md
- name: Kubernetes - Get Namespaces Secrets Name
  x-api-slug: apiv1beta3namespacesnamespacessecretsname-get
  description: Read the specified secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecretsname-get-openapi.md
- name: Kubernetes - Put Namespaces Secrets Name
  x-api-slug: apiv1beta3namespacesnamespacessecretsname-put
  description: Update the specified secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecretsname-put-openapi.md
- name: Kubernetes - Get Secrets
  x-api-slug: apiv1beta3secrets-get
  description: List objects of kind secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3secrets-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Secrets
  x-api-slug: apiv1beta3watchnamespacesnamespacessecrets-get
  description: Watch a list of secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacessecrets-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Secrets Name
  x-api-slug: apiv1beta3watchnamespacesnamespacessecretsname-get
  description: Watch a particular secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacessecretsname-get-openapi.md
- name: Kubernetes - Get Watch Secrets
  x-api-slug: apiv1beta3watchsecrets-get
  description: Watch a list of secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3watchsecrets-get-openapi.md
- name: Kubernetes - Get Namespaces Secrets
  x-api-slug: apiv1beta3namespacesnamespacessecrets-get
  description: List objects of kind secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecrets-get-openapi.md
- name: Kubernetes - Post Namespaces Secrets
  x-api-slug: apiv1beta3namespacesnamespacessecrets-post
  description: Create a secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecrets-post-openapi.md
- name: Kubernetes - Delete Namespaces Secrets Name
  x-api-slug: apiv1beta3namespacesnamespacessecretsname-delete
  description: Delete a secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecretsname-delete-openapi.md
- name: Kubernetes - Get Namespaces Secrets Name
  x-api-slug: apiv1beta3namespacesnamespacessecretsname-get
  description: Read the specified secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecretsname-get-openapi.md
- name: Kubernetes - Put Namespaces Secrets Name
  x-api-slug: apiv1beta3namespacesnamespacessecretsname-put
  description: Update the specified secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3namespacesnamespacessecretsname-put-openapi.md
- name: Kubernetes - Get Secrets
  x-api-slug: apiv1beta3secrets-get
  description: List objects of kind secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3secrets-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Secrets
  x-api-slug: apiv1beta3watchnamespacesnamespacessecrets-get
  description: Watch a list of secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacessecrets-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Secrets Name
  x-api-slug: apiv1beta3watchnamespacesnamespacessecretsname-get
  description: Watch a particular secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespacessecretsname-get-openapi.md
- name: Kubernetes - Get Watch Secrets
  x-api-slug: apiv1beta3watchsecrets-get
  description: Watch a list of secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/secrets/master/_listings/kubernetes/apiv1beta3watchsecrets-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://knoema.api.gallery.streamdata.io
- type: x-api-stack
  url: http://kubernetes.stack.network
- type: x-blog
  url: http://blog.kubernetes.io/
- type: x-blog-rss
  url: http://blog.kubernetes.io/feeds/posts/default
- type: x-github
  url: https://github.com/kubernetes
- type: x-twitter
  url: https://twitter.com/kubernetesio
- type: x-website
  url: http://kubernetes.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---