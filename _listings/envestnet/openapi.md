swagger: "2.0"
x-collection-name: Envestnet
x-complete: 1
info:
  title: Crunch Base
  description: the-crunchbase-api-is-a-relatively-straightforward-rest-service-that-allows-developers-to-access-data-in-the-business-graph-
  termsOfService: https://data.crunchbase.com/v3/page/accessing-the-dataset
  contact:
    name: Crunchbase
    url: https://groups.google.com/forum/#!forum/crunchbase-api
    email: data@crunchbase.com
  version: v3
host: api.crunchbase.com
basePath: /v/3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /people:
    get:
      summary: Get People
      description: Get People
      operationId: people
      x-api-path-slug: people-get
      parameters:
      - in: query
        name: locations
        description: Filter by location names (comma separated, ANDd together) e
      - in: query
        name: name
        description: A full-text query of name only
      - in: query
        name: page
        description: the 1-indexed page number to retrieve
      - in: query
        name: query
        description: A full-text query of name, title, and company
      - in: query
        name: socials
        description: Filter by social media identity (comma separated, ANDd together)
          e
      - in: query
        name: sort_order
        description: The sort order
      - in: query
        name: types
        description: Filter by type (currently, either this is empty, or is simply
          investor)
      - in: query
        name: updated_since
        description: When provided, restricts the result set to People where updated_at
          >= the passed value
      responses:
        200:
          description: OK
      tags:
      - People
  /people/{permalink}:
    get:
      summary: Get People
      description: Get People Using Permalink
      operationId: people
      x-api-path-slug: peoplepermalink-get
      parameters:
      - in: path
        name: permalink
        description: The permalink of the organization
      - in: query
        name: user_key
        description: 'Possible values are: 7a582a92032069b4f775a15b1acbe256'
      responses:
        200:
          description: OK
      tags:
      - People
      - Permalink
  /people/{permalink}/{relationship_name}:
    get:
      summary: Get People Relationships
      description: Get People Relationships
      operationId: peopleRelationships
      x-api-path-slug: peoplepermalinkrelationship-name-get
      parameters:
      - in: query
        name: page
        description: The page number to retrieve
      - in: path
        name: permalink
        description: The permalink of the Person
      - in: path
        name: relationship_name
        description: The name of the relationship to connected Items
      - in: query
        name: sort_order
        description: The sort order
      responses:
        200:
          description: OK
      tags:
      - People
      - Permalink
      - Relationship
      - Name