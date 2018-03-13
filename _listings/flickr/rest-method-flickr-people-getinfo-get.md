---
swagger: "2.0"
info:
  title: Flickr
  version: 1.0.0
host: api.flickr.com
basePath: /services
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest?method=flickr.people.getInfo:
    get:
      summary: Get People
      description: Returns a person
      operationId: getPersonByID
      parameters:
      - in: query
        name: api_key
      - in: query
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - photos
      - people
definitions:
  ContextPhoto:
    properties:
      id:
        description: This is a default description.
        type: post
      secret:
        description: This is a default description.
        type: post
      server:
        description: This is a default description.
        type: post
      farm:
        description: This is a default description.
        type: post
      title:
        description: This is a default description.
        type: post
      url:
        description: This is a default description.
        type: post
      thumb:
        description: This is a default description.
        type: post
      media:
        description: This is a default description.
        type: post
      owner:
        description: This is a default description.
        type: post
      license:
        description: This is a default description.
        type: post
  ContextPhotos:
    properties:
      photos:
        description: This is a default description.
        type: post
  Cover:
    properties:
      id:
        description: This is a default description.
        type: post
      owner:
        description: This is a default description.
        type: post
      secret:
        description: This is a default description.
        type: post
      server:
        description: This is a default description.
        type: post
      farm:
        description: This is a default description.
        type: post
      title:
        description: This is a default description.
        type: post
      ispublic:
        description: This is a default description.
        type: post
      isfriend:
        description: This is a default description.
        type: post
      isfamily:
        description: This is a default description.
        type: post
      "y":
        description: This is a default description.
        type: post
  Group:
    properties:
      id:
        description: This is a default description.
        type: post
      path_alias:
        description: This is a default description.
        type: post
      iconserver:
        description: This is a default description.
        type: post
      iconfarm:
        description: This is a default description.
        type: post
      name:
        description: This is a default description.
        type: post
      description:
        description: This is a default description.
        type: post
      rules:
        description: This is a default description.
        type: post
      members:
        description: This is a default description.
        type: post
      pool_count:
        description: This is a default description.
        type: post
      topic_count:
        description: This is a default description.
        type: post
  Note:
    properties:
      description:
        description: This is a default description.
        type: post
  Owner:
    properties:
      nsid:
        description: This is a default description.
        type: post
      username:
        description: This is a default description.
        type: post
      realname:
        description: This is a default description.
        type: post
      location:
        description: This is a default description.
        type: post
      iconserver:
        description: This is a default description.
        type: post
      iconfarm:
        description: This is a default description.
        type: post
      path_alias:
        description: This is a default description.
        type: post
      noindexfollow:
        description: This is a default description.
        type: post
      ispro:
        description: This is a default description.
        type: post
      is_ad_free:
        description: This is a default description.
        type: post
  Person:
    properties:
      id:
        description: This is a default description.
        type: post
      nsid:
        description: This is a default description.
        type: post
      ispro:
        description: This is a default description.
        type: post
      can_buy_pro:
        description: This is a default description.
        type: post
      iconserver:
        description: This is a default description.
        type: post
      iconfarm:
        description: This is a default description.
        type: post
      path_alias:
        description: This is a default description.
        type: post
      has_stats:
        description: This is a default description.
        type: post
      coverphoto_server:
        description: This is a default description.
        type: post
      coverphoto_farm:
        description: This is a default description.
        type: post
  Photo:
    properties:
      id:
        description: This is a default description.
        type: post
      secret:
        description: This is a default description.
        type: post
      server:
        description: This is a default description.
        type: post
      farm:
        description: This is a default description.
        type: post
      dateuploaded:
        description: This is a default description.
        type: post
      isfavorite:
        description: This is a default description.
        type: post
      license:
        description: This is a default description.
        type: post
      safety_level:
        description: This is a default description.
        type: post
      rotation:
        description: This is a default description.
        type: post
      originalsecret:
        description: This is a default description.
        type: post
  PhotoURLs:
    properties:
      h:
        description: This is a default description.
        type: post
      l:
        description: This is a default description.
        type: post
      s:
        description: This is a default description.
        type: post
      t:
        description: This is a default description.
        type: post
  Tag:
    properties:
      id:
        description: This is a default description.
        type: post
      author:
        description: This is a default description.
        type: post
      authorname:
        description: This is a default description.
        type: post
      raw:
        description: This is a default description.
        type: post
      _content:
        description: This is a default description.
        type: post
      machine_tag:
        description: This is a default description.
        type: post
  Topic:
    properties:
      id:
        description: This is a default description.
        type: post
      subject:
        description: This is a default description.
        type: post
      message:
        description: This is a default description.
        type: post
      author:
        description: This is a default description.
        type: post
      authorname:
        description: This is a default description.
        type: post
      author_path_alias:
        description: This is a default description.
        type: post
      author_is_deleted:
        description: This is a default description.
        type: post
      is_pro:
        description: This is a default description.
        type: post
      role:
        description: This is a default description.
        type: post
      iconserver:
        description: This is a default description.
        type: post
  TopicReply:
    properties:
      id:
        description: This is a default description.
        type: post
      message:
        description: This is a default description.
        type: post
      author:
        description: This is a default description.
        type: post
      authorname:
        description: This is a default description.
        type: post
      author_path_alias:
        description: This is a default description.
        type: post
      author_is_deleted:
        description: This is a default description.
        type: post
      is_pro:
        description: This is a default description.
        type: post
      iconserver:
        description: This is a default description.
        type: post
      iconfarm:
        description: This is a default description.
        type: post
      can_edit:
        description: This is a default description.
        type: post
  URL:
    properties:
      type:
        description: This is a default description.
        type: post
      _content:
        description: This is a default description.
        type: post
  Album:
    properties:
      id:
        description: This is a default description.
        type: post
      primary:
        description: This is a default description.
        type: post
      secret:
        description: This is a default description.
        type: post
      server:
        description: This is a default description.
        type: post
      farm:
        description: This is a default description.
        type: post
      photos:
        description: This is a default description.
        type: post
      videos:
        description: This is a default description.
        type: post
      count_views:
        description: This is a default description.
        type: post
      count_comments:
        description: This is a default description.
        type: post
      can_comment:
        description: This is a default description.
        type: post
x-collection-name: Flickr
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