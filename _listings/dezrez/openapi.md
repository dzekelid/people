swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/appointment/freebusy:
    post:
      summary: Returns Free/Busy information regarding multiple people.
      description: Returns free/busy information regarding multiple people..
      operationId: Appointment_GetFreeBusyByquery
      x-api-path-slug: apiappointmentfreebusy-post
      parameters:
      - in: body
        name: query
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Free
      - Busy
      - Information
      - Regarding
      - Multiple
      - People
  /api/people/findbyemail:
    get:
      summary: Returns a list of people that have the supplied email address.
      description: Returns a list of people that have the supplied email address..
      operationId: People_GetPeopleWithEmailAddressByemailAddress
      x-api-path-slug: apipeoplefindbyemail-get
      parameters:
      - in: query
        name: emailAddress
        description: The email address
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - List
      - Of
      - People
      - That
      - Have
      - Supplied
      - Email
      - Address
  /api/globalsearch/people:
    get:
      summary: Search for People across the system.
      description: Search for people across the system..
      operationId: GlobalSearch_PeopleBydataContract.termBydataContract.pageSizeBydataContract.pageNumberBydataContract
      x-api-path-slug: apiglobalsearchpeople-get
      parameters:
      - in: query
        name: dataContract.branchId
      - in: query
        name: dataContract.excludeArchived
      - in: query
        name: dataContract.excludeDeleted
      - in: query
        name: dataContract.groupTypes
      - in: query
        name: dataContract.lastUpdated
      - in: query
        name: dataContract.pageNumber
      - in: query
        name: dataContract.pageSize
      - in: query
        name: dataContract.serviceType
      - in: query
        name: dataContract.term
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - SearchPeople
      - Across
      - System
  /api/property/{id}/owners:
    get:
      summary: For a given property, will return owning PeopleGroup
      description: For a given property, will return owning peoplegroup.
      operationId: Property_OwnersByid
      x-api-path-slug: apipropertyidowners-get
      parameters:
      - in: path
        name: id
        description: property id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - For
      - Given
      - Property
      - ""
      - Will
      - Return
      - Owning
      - PeopleGroup