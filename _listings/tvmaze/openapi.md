swagger: "2.0"
x-collection-name: TVmaze
x-complete: 1
info:
  title: TVmaze user
  description: access-to-the-user-api-is-only-possible-for-users-with-a-premiumhttpwww-tvmaze-compremium-account--a-user-can-only-access-their-own-user-data-authentication-uses-http-basic--use-the-tvmaze-username-as-authentication-username-and-the-tvmaze-api-key-as-authentication-password--your-api-key-can-be-found-on-your-dashboardhttpwww-tvmaze-comdashboard--to-try-out-these-api-calls-from-this-page-click-the-authorize-button-on-top-and-input-your-credentials-
  version: "1.0"
host: api.tvmaze.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/follows/people:
    get:
      summary: Get User Follows People
      description: Get user follows people.
      operationId: getUserFollowsPeople
      x-api-path-slug: userfollowspeople-get
      parameters:
      - in: query
        name: embed
        description: Embed full person info
      responses:
        200:
          description: OK
      tags:
      - Television
      - User
      - Follows
      - People
  /user/follows/people/{person_id}:
    delete:
      summary: Delete User Follows People Person
      description: Delete user follows people person.
      operationId: deleteUserFollowsPeoplePerson
      x-api-path-slug: userfollowspeopleperson-id-delete
      responses:
        200:
          description: OK
      tags:
      - Television
      - User
      - Follows
      - People
      - Person
    get:
      summary: Get User Follows People Person
      description: Get user follows people person.
      operationId: getUserFollowsPeoplePerson
      x-api-path-slug: userfollowspeopleperson-id-get
      responses:
        200:
          description: OK
      tags:
      - Television
      - User
      - Follows
      - People
      - Person
    parameters:
      summary: Parameters User Follows People Person
      description: Parameters user follows people person.
      operationId: parametersUserFollowsPeoplePerson
      x-api-path-slug: userfollowspeopleperson-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Television
      - Parameters
      - User
      - Follows
      - People
      - Person
    put:
      summary: Put User Follows People Person
      description: Put user follows people person.
      operationId: putUserFollowsPeoplePerson
      x-api-path-slug: userfollowspeopleperson-id-put
      responses:
        200:
          description: OK
      tags:
      - Television
      - User
      - Follows
      - People
      - Person