---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Photos People Delete Coords
  description: Remove the bounding box from a person in a photo
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.people.findByEmail:
    get:
      summary: People Find By Email
      description: Return a user's NSID, given their email address
      operationId: getRestMethodFlickr.people.findbyemail
      x-api-path-slug: restmethodflickr-people-findbyemail-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: find_email
        description: The email address of the user to find (may be primary or secondary)
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - People
      - FindByEmail
  /rest/?method=flickr.people.findByUsername:
    get:
      summary: People Find By Username
      description: Return a user's NSID, given their username.
      operationId: getRestMethodFlickr.people.findbyusername
      x-api-path-slug: restmethodflickr-people-findbyusername-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: username
        description: The username of the user to lookup
      responses:
        200:
          description: OK
      tags:
      - People
      - FindByUsername
  /rest/?method=flickr.people.getInfo:
    get:
      summary: People Get Info
      description: Get information about a user.
      operationId: getRestMethodFlickr.people.getinfo
      x-api-path-slug: restmethodflickr-people-getinfo-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: user_id
        description: The NSID of the user to fetch information about
      responses:
        200:
          description: OK
      tags:
      - People
      - GetInfo
  /rest/?method=flickr.people.getPhotos:
    get:
      summary: People Get Photos
      description: Return photos from the given user's photostream. Only photos visible
        to the calling user will be returned. This method must be authenticated; to
        return public photos for a user, use flickr.people.getPublicPhotos.
      operationId: getRestMethodFlickr.people.getphotos
      x-api-path-slug: restmethodflickr-people-getphotos-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: content_type
        description: Content type setting
      - in: query
        name: extras
        description: A comma-delimited list of extra information to fetch for each
          returned record
      - in: query
        name: format
        description: Response format
      - in: query
        name: max_taken_date
        description: Maximum taken date
      - in: query
        name: max_upload_date
        description: Maximum upload date
      - in: query
        name: min_taken_date
        description: Minimum taken date
      - in: query
        name: min_upload_date
        description: Minimum upload date
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of photos to return per page
      - in: query
        name: privacy_filter
        description: Return photos only matching a certain privacy level
      - in: query
        name: safe_search
        description: Safe search setting
      - in: query
        name: user_id
        description: The NSID of the user whose photos to return
      responses:
        200:
          description: OK
      tags:
      - People
      - GetPhotos
  /rest/?method=flickr.people.getPhotosOf:
    get:
      summary: People Get Photos Of
      description: Returns a list of photos containing a particular Flickr member.
      operationId: getRestMethodFlickr.people.getphotosof
      x-api-path-slug: restmethodflickr-people-getphotosof-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: extras
        description: A comma-delimited list of extra information to fetch for each
          returned record
      - in: query
        name: format
        description: Response format
      - in: query
        name: owner_id
        description: An NSID of a Flickr member
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of photos to return per page
      - in: query
        name: user_id
        description: The NSID of the user you want to find photos of
      responses:
        200:
          description: OK
      tags:
      - People
      - GetPhotosOf
  /rest/?method=flickr.people.getPublicGroups:
    get:
      summary: People Get Public Groups
      description: Returns the list of public groups a user is a member of.
      operationId: getRestMethodFlickr.people.getpublicgroups
      x-api-path-slug: restmethodflickr-people-getpublicgroups-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: user_id
        description: The NSID of the user to fetch groups for
      responses:
        200:
          description: OK
      tags:
      - People
      - GetPublicGroups
  /rest/?method=flickr.people.getPublicPhotos:
    get:
      summary: People Get Public Photos
      description: Get a list of public photos for the given user.
      operationId: getRestMethodFlickr.people.getpublicphotos
      x-api-path-slug: restmethodflickr-people-getpublicphotos-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: extras
        description: A comma-delimited list of extra information to fetch for each
          returned record
      - in: query
        name: format
        description: Response format
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of photos to return per page
      - in: query
        name: safe_search
        description: Safe search setting
      - in: query
        name: user_id
        description: The NSID of the user whose photos to return
      responses:
        200:
          description: OK
      tags:
      - People
      - GetPublicPhotos
  /rest/?method=flickr.people.getUploadStatus:
    get:
      summary: People Get Upload Status
      description: Returns information for the calling user related to photo uploads.
      operationId: getRestMethodFlickr.people.getuploadstatus
      x-api-path-slug: restmethodflickr-people-getuploadstatus-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - People
      - GetUploadStatus
  /rest/?method=flickr.photos.people.add:
    post:
      summary: Photos People Add
      description: Add a person to a photo. Coordinates and sizes are in pixels, based
        on the 500px image size shown on individual photo pages.
      operationId: postRestMethodFlickr.photos.people.add
      x-api-path-slug: restmethodflickr-photos-people-add-post
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: person_h
        description: The height (in pixels) of the box around the person
      - in: query
        name: person_w
        description: The width (in pixels) of the box around the person
      - in: query
        name: person_x
        description: The left-most pixel co-ordinate of the box around the person
      - in: query
        name: person_y
        description: The top-most pixel co-ordinate of the box around the person
      - in: query
        name: photo_id
        description: The id of the photo to add a person to
      - in: query
        name: user_id
        description: The NSID of the user to add to the photo
      responses:
        200:
          description: OK
      tags:
      - Photos
      - People
      - Add
  /rest/?method=flickr.photos.people.delete:
    post:
      summary: Photos People Delete
      description: Remove a person from a photo.
      operationId: postRestMethodFlickr.photos.people.delete
      x-api-path-slug: restmethodflickr-photos-people-delete-post
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: photo_id
        description: The id of the photo to remove a person from
      - in: query
        name: user_id
        description: The NSID of the user to remove from the photo
      responses:
        200:
          description: OK
      tags:
      - Photos
      - People
      - Delete
  /rest/?method=flickr.photos.people.deleteCoords:
    post:
      summary: Photos People Delete Coords
      description: Remove the bounding box from a person in a photo
      operationId: postRestMethodFlickr.photos.people.deletecoords
      x-api-path-slug: restmethodflickr-photos-people-deletecoords-post
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: photo_id
        description: The id of the photo to edit a person in
      - in: query
        name: user_id
        description: The NSID of the user whose bounding box you want to remove
      responses:
        200:
          description: OK
      tags:
      - Photos
      - People
      - DeleteCoords
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