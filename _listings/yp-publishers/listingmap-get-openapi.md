---
swagger: "2.0"
x-collection-name: YP Publishers
x-complete: 0
info:
  title: 'Yellow Pages API '
  description: ""
  termsOfService: http://resourcecenter.yp.com/developer/terms-use
  version: v1
host: api2.yp.com
basePath: /content/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /coupons:
    get:
      summary: Get Business Listing Reviews
      description: Get Business Listing Reviews
      operationId: get-business-listing-reviews
      x-api-path-slug: coupons-get
      parameters:
      - in: query
        name: format
        description: Desired format of the response
      - in: query
        name: searchloc
        description: Unparsed, user-entered search location
      - in: query
        name: term
        description: Unparsed, user-entered search term
      responses:
        200:
          description: OK
      tags:
      - ""
  /deals:
    get:
      summary: Get Coupons Near Location
      description: Get Coupons Near Location
      operationId: get-coupons-near-location
      x-api-path-slug: deals-get
      parameters:
      - in: query
        name: searchloc
        description: Unparsed, user-entered search location
      responses:
        200:
          description: OK
      tags:
      - ""
  /details:
    get:
      summary: Search Listings
      description: Search Listings
      operationId: search-listings
      x-api-path-slug: details-get
      parameters:
      - in: query
        name: format
        description: Desired format of the response
      - in: query
        name: listingid
        description: The unique identifier for the business listing
      - in: query
        name: User-Agent
        description: User agent
      responses:
        200:
          description: OK
      tags:
      - ""
  /listingmap:
    get:
      summary: ""
      description: ""
      operationId: ""
      x-api-path-slug: listingmap-get
      parameters:
      - in: query
        name: image_format
        description: String representing the mime-type of map you want returned
      - in: query
        name: listingid
        description: YP listing ID
      - in: query
        name: pan_horizontal
        description: A positive or negative number reflecting the percentage of the
          map image to pan west (negative) or east (positive)
      - in: query
        name: pan_vertical
        description: A positive or negative number reflecting the percentage of the
          map image to pan south (negative) or north (positive)
      - in: query
        name: pixel_height
        description: Integer representing the height in pixels of the map (Default
          = 400)
      - in: query
        name: pixel_width
        description: Integer representing the width in pixels of the map (Default
          = 400)
      - in: query
        name: zoom
        description: 'Sets the zoom factor for the map, expressed as a fraction from '
      responses:
        200:
          description: OK
      tags:
      - ""
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