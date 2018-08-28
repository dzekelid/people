---
swagger: "2.0"
info:
  title: Clearbit Person Retrieves a person and company by email address
  description: Retrieves a person and company by email address.
  version: v1
host: person.clearbit.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /combined/find:
    get:
      summary: Retrieves a person and company by email address
      description: Retrieves a person and company by email address
      operationId: getCombined
      parameters:
      - in: query
        name: email
        description: the person's email address
      responses:
        200:
          description: OK
      tags:
      - people
definitions:
  image:
    properties:
      image:
        description: Image returned
        type: string
  Combined:
    properties: []
  Geo:
    properties:
      streetNumber:
        description: This is a default description.
        type: get
      streetName:
        description: This is a default description.
        type: get
      subPremise:
        description: This is a default description.
        type: get
      city:
        description: This is a default description.
        type: get
      state:
        description: This is a default description.
        type: get
      stateCode:
        description: This is a default description.
        type: get
      postalCode:
        description: This is a default description.
        type: get
      country:
        description: This is a default description.
        type: get
      countryCode:
        description: This is a default description.
        type: get
      lat:
        description: This is a default description.
        type: get
  Person:
    properties:
      id:
        description: This is a default description.
        type: get
      fuzzy:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      gender:
        description: This is a default description.
        type: get
      location:
        description: This is a default description.
        type: get
      timeZone:
        description: This is a default description.
        type: get
      utcOffset:
        description: This is a default description.
        type: get
      bio:
        description: This is a default description.
        type: get
      site:
        description: This is a default description.
        type: get
      avatar:
        description: This is a default description.
        type: get
  Company:
    properties:
      id:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      legalName:
        description: This is a default description.
        type: get
      domain:
        description: This is a default description.
        type: get
      domainAliases:
        description: This is a default description.
        type: get
      category:
        description: This is a default description.
        type: get
      site:
        description: This is a default description.
        type: get
      description:
        description: This is a default description.
        type: get
      tags:
        description: This is a default description.
        type: get
      foundedDate:
        description: This is a default description.
        type: get
x-collection-name: Clearbit
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