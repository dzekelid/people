swagger: "2.0"
x-collection-name: BBC
x-complete: 1
info:
  title: BBC Nitro
  description: bbc-nitro-is-the-bbcs-application-programming-interface-api-for-bbc-programmes-metadata-
  termsOfService: http://www.bbc.co.uk/terms/
  contact:
    name: Open Nitro Project
    url: http://developer.bbc.co.uk/
    email: nitro@bbc.co.uk
  version: 1.0.0
host: programmes.api.bbc.com
basePath: /nitro/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /people:
    get:
      summary: 'Find the people behind and in programmes: cast, crew, guests and more'
      description: The People feed allows you to search for the people and groups
        that contribute to programmes. This is the starting point for cast and crew
        credits, as well as finding contributors using external IDs (such as Wikipedia
        URLs)
      operationId: listPeople
      x-api-path-slug: people-get
      parameters:
      - in: query
        name: authority
        description: filter for subset of people that have an ID issued by the given
          authority
      - in: query
        name: has_external_id
        description: filter for people who have an external identifier
      - in: query
        name: id
        description: filter for subset of people having given ID
      - in: query
        name: id_type
        description: filter for subset of people that have given an ID of the given
          type
      - in: query
        name: page
        description: which page of results to return
      - in: query
        name: page_size
        description: number of results in each page
      - in: query
        name: partner_id
        description: filter for people by partner ID
      - in: query
        name: partner_pid
        description: filter for people by partner PID
      - in: query
        name: pid
        description: filter for subset of people having given PID
      - in: query
        name: programme
        description: filter for subset of people that have contributed to the given
          programme pid
      - in: query
        name: q
        description: filter for subset of people matching supplied keyword/phrase
          (boolean operators permitted)
      responses:
        200:
          description: OK
      tags:
      - People