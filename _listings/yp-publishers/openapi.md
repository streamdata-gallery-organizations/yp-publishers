---
swagger: "2.0"
x-collection-name: YP Publishers
x-complete: 1
info:
  title: Yellow Pages API
  description: the-yp-developer-program-provides-open-apis-to-access-listings-data-user-ratings-coupons-and-functionality-such-as-local-search-and-mapping-
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
  /reviews:
    get:
      summary: Get Business Listing Details
      description: Get Business Listing Details
      operationId: get-business-listing-details
      x-api-path-slug: reviews-get
      parameters:
      - in: query
        name: format
        description: Desired format of the response
      - in: query
        name: listingid
        description: The unique identifier for the business listing
      responses:
        200:
          description: OK
      tags:
      - ""
  /search:
    get:
      summary: Get Business Listing Map
      description: Get Business Listing Map
      operationId: get-business-listing-map
      x-api-path-slug: search-get
      parameters:
      - in: query
        name: format
        description: Desired format of the response
      - in: query
        name: listingcount
        description: Total number of listings to return
      - in: query
        name: pagenum
        description: The page index of the block of results to return
      - in: query
        name: phonesearch
        description: Indicates that the term parameter contains a phone number, formatted
          as a 10-digit integer, e
      - in: query
        name: radius
        description: Maximum search radius (in miles) from center of target location
          for Organic Results (only)
      - in: query
        name: searchloc
        description: Unparsed, user-entered search location
      - in: query
        name: shorturl
        description: Enables short URL formats in the API response
      - in: query
        name: sort
        description: Select the sort criteria for Organic Listings (only)
      - in: query
        name: term
        description: Unparsed, user-entered search term
      - in: query
        name: User-Agent
        description: User agent
      responses:
        200:
          description: OK
      tags:
      - ""
---