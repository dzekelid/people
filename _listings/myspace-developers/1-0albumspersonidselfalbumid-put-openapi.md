---
swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 0
info:
  title: My Space Put Albums Personid Self Albums
  description: Update an Album.
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
  /1.0/statusmoodcomments/{personId}/@self/{statusId}:
    post:
      summary: Post Statusmoodcomments Personid Self Statusid
      description: Posts a comment to a status.
      operationId: 1.0.statusmoodcomments.personId._self.statusId.post
      x-api-path-slug: 1-0statusmoodcommentspersonidselfstatusid-post
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: selector
        description: Indicates which set of individuals to query for activities
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      - in: path
        name: statusId
        description: Specifies which status or mood to post a comment for
      responses:
        200:
          description: OK
      tags:
      - Statusmoodcomments
      - People
      - Self
      - StatusId
  /1.0/statusmood/{personId}/{selector}/{friendId}/history:
    get:
      summary: Get Statusmood Personid Selector Friendid History
      description: Returns History Friend.
      operationId: 1.0.statusmood.personId.selector.friendId.history.get
      x-api-path-slug: 1-0statusmoodpersonidselectorfriendidhistory-get
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
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
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
      - Statusmood
      - People
      - Selector
      - FriendId
      - History
  /1.0/statusmood/{personId}/{selector}/{friendId}:
    get:
      summary: Get Statusmood Personid Selector Friendid
      description: Returns a status for Friend.
      operationId: 1.0.statusmood.personId.selector.friendId.get
      x-api-path-slug: 1-0statusmoodpersonidselectorfriendid-get
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
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
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
      - Statusmood
      - People
      - Selector
      - FriendId
  /1.0/statusmood/{personId}/{selector}/history:
    get:
      summary: Get Statusmood Personid Selector History
      description: Returns History User.
      operationId: 1.0.statusmood.personId.selector.history.get
      x-api-path-slug: 1-0statusmoodpersonidselectorhistory-get
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
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
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
      - Statusmood
      - People
      - Selector
      - History
  /1.0/statusmood/{personId}/{selector}:
    put:
      summary: Put Statusmood Personid Selector
      description: Updates a status for User.
      operationId: 1.0.statusmood.personId.selector.put
      x-api-path-slug: 1-0statusmoodpersonidselector-put
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
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
      - Statusmood
      - People
      - Selector
    get:
      summary: Get Statusmood Personid Selector
      description: Returns a status for User.
      operationId: 1.0.statusmood.personId.selector.get
      x-api-path-slug: 1-0statusmoodpersonidselector-get
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
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
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
      - Statusmood
      - People
      - Selector
  /1.0/statusmood/{personId}/@supportedMood/{moodId}:
    put:
      summary: Put Statusmood Personid @supportedmood Moodid
      description: Updates a mood.
      operationId: 1.0.statusmood.personId._supportedMood.moodId.put
      x-api-path-slug: 1-0statusmoodpersonidsupportedmoodmoodid-put
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: moodId
        description: The integer value of the specific mood that you want to retrieve
          data for
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Statusmood
      - People
      - Supported
      - Mood
      - MoodId
    get:
      summary: Get Statusmood Personid @supportedmood Moodid
      description: Retrieves a mood.
      operationId: 1.0.statusmood.personId._supportedMood.moodId.get
      x-api-path-slug: 1-0statusmoodpersonidsupportedmoodmoodid-get
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
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: moodId
        description: The integer value of the specific mood that you want to retrieve
          data for
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Statusmood
      - People
      - Supported
      - Mood
      - MoodId
  /1.0/statusmood/{personId}/@supportedMood:
    post:
      summary: Post Statusmood Personid @supportedmood
      description: Adds a mood.
      operationId: 1.0.statusmood.personId._supportedMood.post
      x-api-path-slug: 1-0statusmoodpersonidsupportedmood-post
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: filterBy
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Statusmood
      - People
      - Supported
      - Mood
    get:
      summary: Get Statusmood Personid @supportedmood
      description: Retrieves all supported moods.
      operationId: 1.0.statusmood.personId._supportedMood.get
      x-api-path-slug: 1-0statusmoodpersonidsupportedmood-get
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
        description: 'See: http://wiki'
      - in: query
        name: filterOp
        description: 'See: http://wiki'
      - in: query
        name: filterValue
        description: 'See: http://wiki'
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Statusmood
      - People
      - Supported
      - Mood
  /1.0/mediaitemcomments/{personId}/@self/{albumId}/{mediaItemId}:
    get:
      summary: Get Mediaitemcomments Personid Self Albums Mediaitemid
      description: Retrieves item comments from a specified album.
      operationId: 1.0.mediaitemcomments.personId._self.albumId.mediaItemId.get
      x-api-path-slug: 1-0mediaitemcommentspersonidselfalbumidmediaitemid-get
      parameters:
      - in: path
        name: albumId
        description: Indicates which single album from the group identified by {selector}
          should be returned
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
      - in: path
        name: mediaItemId
        description: Indicates which single media item from the album identified by
          {albumId} should be returned
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Mediaitemcomments
      - People
      - Self
      - AlbumId
      - MediaItemId
  /1.0/mediaItems/{personId}/@videos/@supportedcategories/{categoryId}:
    get:
      summary: Get Mediaitems Personid Videos Supported Categories Categoryid
      description: Retrieves videos for Category.
      operationId: 1.0.mediaItems.personId._videos._supportedcategories.categoryId.get
      x-api-path-slug: 1-0mediaitemspersonidvideossupportedcategoriescategoryid-get
      parameters:
      - in: path
        name: categoryId
        description: Indicates the video category about which you want to retrieve
          data
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
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - '@videos'
      - Supported
      - categories
      - CategoryId
  /1.0/mediaItems/{personId}/@videos/@supportedcategories:
    get:
      summary: Get Mediaitems Personid Videos Supported Categories
      description: Retrieves supported categories.
      operationId: 1.0.mediaItems.personId._videos._supportedcategories.get
      x-api-path-slug: 1-0mediaitemspersonidvideossupportedcategories-get
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
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - '@videos'
      - Supported
      - categories
  /1.0/mediaItems/{personId}/@self/@videos/{mediaItemId}:
    put:
      summary: Put Mediaitems Personid Self Videos Mediaitemid
      description: Updates an video.
      operationId: 1.0.mediaItems.personId._self._videos.mediaItemId.put
      x-api-path-slug: 1-0mediaitemspersonidselfvideosmediaitemid-put
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
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
      - in: path
        name: mediaItemId
        description: Indicates which single media item should be returned
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - Self
      - '@videos'
      - MediaItemId
    get:
      summary: Get Mediaitems Personid Self Videos Mediaitemid
      description: Retrieves a video.
      operationId: 1.0.mediaItems.personId._self._videos.mediaItemId.get
      x-api-path-slug: 1-0mediaitemspersonidselfvideosmediaitemid-get
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
      - in: path
        name: mediaItemId
        description: Indicates which single media item should be returned
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - Self
      - '@videos'
      - MediaItemId
  /1.0/mediaItems/{personId}/@self/@videos:
    post:
      summary: Post Mediaitems Personid Self Videos
      description: Adds videos from a specified album.
      operationId: 1.0.mediaItems.personId._self._videos.post
      x-api-path-slug: 1-0mediaitemspersonidselfvideos-post
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
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
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - Self
      - '@videos'
    get:
      summary: Get Mediaitems Personid Self Videos
      description: Retrieves all the videos.
      operationId: 1.0.mediaItems.personId._self._videos.get
      x-api-path-slug: 1-0mediaitemspersonidselfvideos-get
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
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - Self
      - '@videos'
  /1.0/mediaItems/{personId}/@self/{albumId}/{mediaItemId}:
    put:
      summary: Put Mediaitems Personid Self Albums Mediaitemid
      description: Updates an item from a specified album.
      operationId: 1.0.mediaItems.personId._self.albumId.mediaItemId.put
      x-api-path-slug: 1-0mediaitemspersonidselfalbumidmediaitemid-put
      parameters:
      - in: path
        name: albumId
        description: Indicates which single album from the group identified by {selector}
          should be returned
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
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
      - in: path
        name: mediaItemId
        description: Indicates which single media item from the album identified by
          {albumId} should be returned
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - Self
      - AlbumId
      - MediaItemId
    get:
      summary: Get Mediaitems Personid Self Albums Mediaitemid
      description: Retrieves an item from a specified album.
      operationId: 1.0.mediaItems.personId._self.albumId.mediaItemId.get
      x-api-path-slug: 1-0mediaitemspersonidselfalbumidmediaitemid-get
      parameters:
      - in: path
        name: albumId
        description: Indicates which single album from the group identified by {selector}
          should be returned
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
      - in: path
        name: mediaItemId
        description: Indicates which single media item from the album identified by
          {albumId} should be returned
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - Self
      - AlbumId
      - MediaItemId
  /1.0/mediaItems/{personId}/@self/{albumId}:
    post:
      summary: Post Mediaitems Personid Self Albums
      description: Adds items from a specified album.
      operationId: 1.0.mediaItems.personId._self.albumId.post
      x-api-path-slug: 1-0mediaitemspersonidselfalbumid-post
      parameters:
      - in: path
        name: albumId
        description: Indicates which single album from the group identified by {selector}
          should be returned
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
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
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - Self
      - AlbumId
    get:
      summary: Get Mediaitems Personid Self Albums
      description: Retrieves items from a specified album.
      operationId: 1.0.mediaItems.personId._self.albumId.get
      x-api-path-slug: 1-0mediaitemspersonidselfalbumid-get
      parameters:
      - in: path
        name: albumId
        description: Indicates which single album from the group identified by {selector}
          should be returned
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
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - Self
      - AlbumId
  /opensearch/people:
    get:
      summary: Get Opensearch People
      description: Returns search results for people.
      operationId: opensearch.people.get
      x-api-path-slug: opensearchpeople-get
      parameters:
      - in: query
        name: count
        description: Number of items to return
      - in: query
        name: countryCode
        description: Country code to search with
      - in: query
        name: culture
        description: The culture context of the search
      - in: query
        name: distance
        description: Distance away from location to return results
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: gender
        description: The gender to filter on
      - in: query
        name: hasPhoto
        description: Filter for only those who have a photo
      - in: query
        name: latitude
        description: Geographic latitude
      - in: query
        name: location
        description: The location field, such as city, state and/or country
      - in: query
        name: longitude
        description: Geographic longitude
      - in: query
        name: maxAge
        description: Maximum age for returned people
      - in: query
        name: minAge
        description: Minimum age for returned people
      - in: query
        name: searchBy
        description: Which field the search should go through
      - in: query
        name: searchTerms
        description: Free form search terms or query words
      - in: query
        name: startPage
        description: Which page to start at for the results
      responses:
        200:
          description: OK
      tags:
      - Opensearch
      - People
  /1.0/profilecomments/{personId}/@self:
    get:
      summary: Get Profilecomments Personid Self
      description: Retrieves profile comments.
      operationId: 1.0.profilecomments.personId._self.get
      x-api-path-slug: 1-0profilecommentspersonidself-get
      parameters:
      - in: path
        name: personId
        description: The persons identifier
      responses:
        200:
          description: OK
      tags:
      - Profilecomments
      - People
      - Self
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
  /1.0/appdata/{personId}/{selector}/{appId}:
    delete:
      summary: Delete Appdata Personid Selector Appid
      description: Deletes a specified user's application data.
      operationId: 1.0.appdata.personId.selector.appId.delete
      x-api-path-slug: 1-0appdatapersonidselectorappid-delete
      parameters:
      - in: path
        name: appId
        description: The applications ID associated with the OAuth ConsumerKey/ConsumerSecret
          pair
      - in: query
        name: fields
        description: The fields correspond to keys in the application data
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      responses:
        200:
          description: OK
      tags:
      - Appdata
      - People
      - Selector
      - AppId
    post:
      summary: Post Appdata Personid Selector Appid
      description: Adds or updates a specified user's application data.
      operationId: 1.0.appdata.personId.selector.appId.post
      x-api-path-slug: 1-0appdatapersonidselectorappid-post
      parameters:
      - in: path
        name: appId
        description: The applications ID associated with the OAuth ConsumerKey/ConsumerSecret
          pair
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: fields
        description: The fields correspond to keys in the application data
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      responses:
        200:
          description: OK
      tags:
      - Appdata
      - People
      - Selector
      - AppId
    get:
      summary: Get Appdata Personid Selector Appid
      description: Retrieves all application data for a specified user.
      operationId: 1.0.appdata.personId.selector.appId.get
      x-api-path-slug: 1-0appdatapersonidselectorappid-get
      parameters:
      - in: path
        name: appId
        description: The applications ID associated with the OAuth ConsumerKey/ConsumerSecret
          pair
      - in: query
        name: fields
        description: The fields correspond to keys in the application data
      - in: query
        name: format
        description: Determines the format of the response
      - in: path
        name: personId
        description: The persons identifier
      - in: path
        name: selector
        description: Indicates which set of individuals to query for activities
      responses:
        200:
          description: OK
      tags:
      - Appdata
      - People
      - Selector
      - AppId
  /1.0/notifications/{personId}/@self:
    post:
      summary: Post Notifications Personid Self
      description: Sends notification.
      operationId: 1.0.notifications.personId._self.post
      x-api-path-slug: 1-0notificationspersonidself-post
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: path
        name: personId
        description: The persons identifier
      responses:
        200:
          description: OK
      tags:
      - Notifications
      - People
      - Self
  /1.0/groups/{personId}:
    get:
      summary: Get Groups Personid
      description: Retrieves the current user's groups.
      operationId: 1.0.groups.personId.get
      x-api-path-slug: 1-0groupspersonid-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: 'The following field names are supported: id and title'
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Groups
      - People
  /1.0/albums/{personId}/@self/{albumId}:
    put:
      summary: Put Albums Personid Self Albums
      description: Update an Album.
      operationId: 1.0.albums.personId._self.albumId.put
      x-api-path-slug: 1-0albumspersonidselfalbumid-put
      parameters:
      - in: path
        name: albumId
        description: Indicates which single album should be returned
      - in: header
        name: Content-Type
        description: Specifies Content Type
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: path
        name: personId
        description: The persons identifier
      responses:
        200:
          description: OK
      tags:
      - Albums
      - People
      - Self
      - AlbumId
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