---
name: Actility
x-slug: actility
description: 'Actility is the leader in low power wide area (LoRaWAN and 3GPP) network
  connectivity management for the Internet of Things: the ThingPark platform'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
x-kinRank: "7"
x-alexaRank: "637591"
tags: Dataflow
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/dataflow/master/_listings/actility/apis.md
specificationVersion: "0.14"
apis:
- name: ThingPark DX Dataflow API - Bridge dataflow creation
  x-api-slug: bridgedataflows-post
  description: Creates a new Bridge dataflow.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/dataflow/master/_listings/actility/bridgedataflows-post-openapi.md
- name: ThingPark DX Dataflow API - Bridge dataflow retrieval
  x-api-slug: bridgedataflowsbridgedataflowref-get
  description: Retrieves the Bridge dataflow corresponding to the provided order ref,
    if that order is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/dataflow/master/_listings/actility/bridgedataflowsbridgedataflowref-get-openapi.md
- name: ThingPark DX Dataflow API - Bridge dataflow update
  x-api-slug: bridgedataflowsbridgedataflowref-put
  description: Updates the Bridge dataflow corresponding to the provided Bridge dataflow
    ref, if that dataflow is within authorized scopes. Note that when updating a dataflow,
    all existing attributs must be provided next to your changes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/dataflow/master/_listings/actility/bridgedataflowsbridgedataflowref-put-openapi.md
- name: ThingPark DX Dataflow API - Bridge dataflow deletion
  x-api-slug: bridgedataflowsbridgedataflowref-delete
  description: Deletes the Bridge dataflow corresponding to the provided Bridge dataflow
    ref, if that dataflow is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/dataflow/master/_listings/actility/bridgedataflowsbridgedataflowref-delete-openapi.md
- name: ThingPark DX Dataflow API - Dataflow events retrieval
  x-api-slug: events-get
  description: Retrieves the list of events for all configured dataflows in scope.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/dataflow/master/_listings/actility/events-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.actility.com/blog/feed/
- type: x-github
  url: https://github.com/actility
- type: x-openapi
  url: https://dx-api.thingpark.com/core/latest/tpdx-core-api-contract.json
- type: x-api-gallery
  url: http://actility.api.gallery.streamdata.io
- type: x-api-stack
  url: http://actility.stack.network
- type: x-blog
  url: https://www.actility.com/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/actility
- type: x-developer
  url: https://www.actility.com/developer/
- type: x-twitter
  url: https://twitter.com/Actility
- type: x-website
  url: https://www.actility.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---