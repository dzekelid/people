---
swagger: "2.0"
info:
  title: Google People API Get People
  description: |-
    Provides information about a list of specific people by specifying a list
    of requested resource names. Use `people/me` to indicate the authenticated
    user.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: people.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/people:batchGet:
    get:
      summary: Get People
      description: |-
        Provides information about a list of specific people by specifying a list
        of requested resource names
      operationId: people.people.getBatchGet
      parameters:
      - in: query
        name: requestMask.includeField
        description: Comma-separated list of fields to be included in the response
      - in: query
        name: resourceNames
        description: |-
          The resource name, such as one returned by
          [`people
      responses:
        200:
          description: OK
      tags:
      - people
definitions:
  Address:
    properties:
      city:
        description: This is a default description.
        type: parameters
      country:
        description: This is a default description.
        type: parameters
      countryCode:
        description: This is a default description.
        type: parameters
      extendedAddress:
        description: This is a default description.
        type: parameters
      formattedType:
        description: This is a default description.
        type: parameters
      formattedValue:
        description: This is a default description.
        type: parameters
      poBox:
        description: This is a default description.
        type: parameters
      postalCode:
        description: This is a default description.
        type: parameters
      region:
        description: This is a default description.
        type: parameters
      streetAddress:
        description: This is a default description.
        type: parameters
  AgeRangeType:
    properties:
      ageRange:
        description: This is a default description.
        type: parameters
  Biography:
    properties:
      contentType:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  Birthday:
    properties:
      text:
        description: This is a default description.
        type: parameters
  BraggingRights:
    properties:
      value:
        description: This is a default description.
        type: parameters
  ContactGroupMembership:
    properties:
      contactGroupId:
        description: This is a default description.
        type: parameters
  CoverPhoto:
    properties:
      default:
        description: This is a default description.
        type: parameters
      url:
        description: This is a default description.
        type: parameters
  Date:
    properties:
      day:
        description: This is a default description.
        type: parameters
      month:
        description: This is a default description.
        type: parameters
      year:
        description: This is a default description.
        type: parameters
  DomainMembership:
    properties:
      inViewerDomain:
        description: This is a default description.
        type: parameters
  EmailAddress:
    properties:
      displayName:
        description: This is a default description.
        type: parameters
      formattedType:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  Event:
    properties:
      formattedType:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  FieldMetadata:
    properties:
      primary:
        description: This is a default description.
        type: parameters
      verified:
        description: This is a default description.
        type: parameters
  Gender:
    properties:
      formattedValue:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  GetPeopleResponse:
    properties:
      responses:
        description: This is a default description.
        type: parameters
  ImClient:
    properties:
      formattedProtocol:
        description: This is a default description.
        type: parameters
      formattedType:
        description: This is a default description.
        type: parameters
      protocol:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
      username:
        description: This is a default description.
        type: parameters
  Interest:
    properties:
      value:
        description: This is a default description.
        type: parameters
  ListConnectionsResponse:
    properties:
      connections:
        description: This is a default description.
        type: parameters
      nextPageToken:
        description: This is a default description.
        type: parameters
      nextSyncToken:
        description: This is a default description.
        type: parameters
  Locale:
    properties:
      value:
        description: This is a default description.
        type: parameters
  Membership:
    properties: []
  Name:
    properties:
      displayName:
        description: This is a default description.
        type: parameters
      displayNameLastFirst:
        description: This is a default description.
        type: parameters
      familyName:
        description: This is a default description.
        type: parameters
      givenName:
        description: This is a default description.
        type: parameters
      honorificPrefix:
        description: This is a default description.
        type: parameters
      honorificSuffix:
        description: This is a default description.
        type: parameters
      middleName:
        description: This is a default description.
        type: parameters
      phoneticFamilyName:
        description: This is a default description.
        type: parameters
      phoneticFullName:
        description: This is a default description.
        type: parameters
      phoneticGivenName:
        description: This is a default description.
        type: parameters
  Nickname:
    properties:
      type:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  Occupation:
    properties:
      value:
        description: This is a default description.
        type: parameters
  Organization:
    properties:
      current:
        description: This is a default description.
        type: parameters
      department:
        description: This is a default description.
        type: parameters
      domain:
        description: This is a default description.
        type: parameters
      formattedType:
        description: This is a default description.
        type: parameters
      jobDescription:
        description: This is a default description.
        type: parameters
      location:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      phoneticName:
        description: This is a default description.
        type: parameters
      symbol:
        description: This is a default description.
        type: parameters
      title:
        description: This is a default description.
        type: parameters
  Person:
    properties:
      addresses:
        description: This is a default description.
        type: parameters
      ageRange:
        description: This is a default description.
        type: parameters
      ageRanges:
        description: This is a default description.
        type: parameters
      biographies:
        description: This is a default description.
        type: parameters
      birthdays:
        description: This is a default description.
        type: parameters
      braggingRights:
        description: This is a default description.
        type: parameters
      coverPhotos:
        description: This is a default description.
        type: parameters
      emailAddresses:
        description: This is a default description.
        type: parameters
      etag:
        description: This is a default description.
        type: parameters
      events:
        description: This is a default description.
        type: parameters
  PersonMetadata:
    properties:
      deleted:
        description: This is a default description.
        type: parameters
      linkedPeopleResourceNames:
        description: This is a default description.
        type: parameters
      objectType:
        description: This is a default description.
        type: parameters
      previousResourceNames:
        description: This is a default description.
        type: parameters
      sources:
        description: This is a default description.
        type: parameters
  PersonResponse:
    properties:
      httpStatusCode:
        description: This is a default description.
        type: parameters
      requestedResourceName:
        description: This is a default description.
        type: parameters
  PhoneNumber:
    properties:
      canonicalForm:
        description: This is a default description.
        type: parameters
      formattedType:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  Photo:
    properties:
      url:
        description: This is a default description.
        type: parameters
  ProfileMetadata:
    properties:
      objectType:
        description: This is a default description.
        type: parameters
  Relation:
    properties:
      formattedType:
        description: This is a default description.
        type: parameters
      person:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  RelationshipInterest:
    properties:
      formattedValue:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  RelationshipStatus:
    properties:
      formattedValue:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  Residence:
    properties:
      current:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
  Skill:
    properties:
      value:
        description: This is a default description.
        type: parameters
  Source:
    properties:
      etag:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  Tagline:
    properties:
      value:
        description: This is a default description.
        type: parameters
  Url:
    properties:
      formattedType:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
      value:
        description: This is a default description.
        type: parameters
x-collection-name: Google People
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---