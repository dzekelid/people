swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 1
info:
  title: My Space
  description: create-apps-and-games-within-the-myspace-platform--monetize-through-advertising-and-virtual-goods-
  version: 1.0.0
host: api.myspace.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1.0/people/@supportedFields:
    get:
      summary: Get People Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.people._supportedFields.get
      x-api-path-slug: 1-0peoplesupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - People
      - Supported
      - Fields
  /1.0/people/{personId}/{selector}:
    get:
      summary: Get People Personid Selector
      description: Retrieves user data.
      operationId: 1.0.people.personId.selector.get
      x-api-path-slug: 1-0peoplepersonidselector-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: '@friends, hasapp, @topfriends, @toponlinefriends,networkpresence'
      - in: query
        name: filterOp
        description: 'contains, equalsSee: http://wiki'
      - in: query
        name: filterValue
        description: ', online, true|false See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - People
      - People
      - Selector
  /1.0/people/{personId}/{selector}/{friendId}:
    get:
      summary: Get People Personid Selector Friendid
      description: Retrieves friend data.
      operationId: 1.0.people.personId.selector.friendId.get
      x-api-path-slug: 1-0peoplepersonidselectorfriendid-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: '@friends, hasapp, @topfriends, @toponlinefriends,networkpresence'
      - in: query
        name: filterOp
        description: 'contains, equalsSee: http://wiki'
      - in: query
        name: filterValue
        description: ', online, true|false See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: friendId
        description: Is the same as {personId}, but for the persons friend
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - People
      - People
      - Selector
      - FriendId