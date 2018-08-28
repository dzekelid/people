---
name: Google People
x-slug: google-people
description: The People API lets you list authenticated users Contacts and retrieve
  profile information for authenticated users and their contacts. For example, lets
  say the authenticated user, Jen, has Fabian and Ranjith in her private contacts.
  When your app calls people.connections.list to retrieve a list of her connections,
  Jen is presented with a consent screen asking to give the app access to the list.
  If Jen consents, the app retrieves a list containing Fabian and Ranjith (with a
  resource name for each person). The app can then call people.get, passing in a resource
  name, to get private contact and public profile data for each person.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-people.png
x-kinRank: "9"
x-alexaRank: "0"
tags: People
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/people/master/_listings/google-people/apis.md
specificationVersion: "0.14"
apis:
- name: Google People - Get People
  x-api-slug: v1peoplebatchget-get
  description: |-
    Provides information about a list of specific people by specifying a list
    of requested resource names. Use `people/me` to indicate the authenticated
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-people.png
  humanURL: https://developers.google.com/people/
  baseURL: ://people.googleapis.com//
  tags: Users, People, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/people/master/_listings/google-people/v1peoplebatchget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/people/master/_listings/google-people/v1peoplebatchget-get-openapi.md
- name: Google People - Get Person
  x-api-slug: v1resourcename-get
  description: |-
    Provides information about a person resource for a resource name. Use
    `people/me` to indicate the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-people.png
  humanURL: https://developers.google.com/people/
  baseURL: ://people.googleapis.com//
  tags: Users, People, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/people/master/_listings/google-people/v1resourcename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/people/master/_listings/google-people/v1resourcename-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.partners.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.people.stack.network
- type: x-code
  url: https://developers.google.com/people/v1/libraries
- type: x-terms-of-service
  url: https://developers.google.com/people/terms
- type: x-website
  url: https://developers.google.com/people/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---