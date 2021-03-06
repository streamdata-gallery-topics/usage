---
name: Predix
x-slug: predix
description: Predix (IoT PaaS) helps you develop apps that connect people with industrial
  machines through analytics and data for better business outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
x-kinRank: "7"
x-alexaRank: "264121"
tags: Usage
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/usage/master/_listings/predix/apis.md
specificationVersion: "0.14"
apis:
- name: Enterprise Connect API (osaka.67) - Validate the EC service memory usage
  x-api-slug: healthmemory-get
  description: Validate the EC gateway memory usage
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https://ec-predix-service-osaka.run.aws-usw02-pr.ice.predix.io//v1
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/usage/master/_listings/predix/healthmemory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/usage/master/_listings/predix/healthmemory-get-openapi.md
- name: Enterprise Connect API (osaka.67) - Report usage
  x-api-slug: reportsusage-post
  description: Report usage by zoneid
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https://ec-predix-service-osaka.run.aws-usw02-pr.ice.predix.io//v1
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/usage/master/_listings/predix/reportsusage-post-openapi.md
- name: Enterprise Connect API (osaka.67) - Get last usage
  x-api-slug: reportsusage-get
  description: get last usage by zoneid
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https://ec-predix-service-osaka.run.aws-usw02-pr.ice.predix.io//v1
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/usage/master/_listings/predix/reportsusage-get-openapi.md
- name: Notification Service Documentation - Get Tenants Usage
  x-api-slug: v1tenantstenant-uuidusage-get
  description: Get tenants usage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https://ev-notification-service.run.aws-usw02-pr.ice.predix.io//
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/usage/master/_listings/predix/v1tenantstenant-uuidusage-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://predicthq.api.gallery.streamdata.io
- type: x-api-stack
  url: http://predix.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/predix
- type: x-documentation
  url: https://docs.predix.io/en-US/platform
- type: x-twitter
  url: https://twitter.com/Predix
- type: x-website
  url: https://www.predix.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---