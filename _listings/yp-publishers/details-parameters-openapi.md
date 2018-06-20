---
swagger: "2.0"
x-collection-name: YP Publishers
x-complete: 0
info:
  title: US Yellow Pages Parameters Details
  description: Parameters details.
  version: 1.0.0
host: api2.yp.com
basePath: /content/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /listingmap:
    parameters:
      summary: Parameters Listingmap
      description: Parameters listingmap.
      operationId: parametersListingmap
      x-api-path-slug: listingmap-parameters
      responses:
        200:
          description: OK
      tags:
      - Listingmap
    get:
      summary: Get Listingmap
      description: Returns an URL for a graphical map for a specified business listing.
      operationId: getListingmap
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
      - Listingmap
  /search:
    parameters:
      summary: Parameters Search
      description: Parameters search.
      operationId: parametersSearch
      x-api-path-slug: search-parameters
      responses:
        200:
          description: OK
      tags:
      - Search
    get:
      summary: Get Search
      description: Supports a number of specific use cases for finding a listing.
        The search request must include a searchloc value to set the geographic context
        for the search. The term value can include both name and category keywords.
        Note that if your implementation uses a single search box, you can combine
        geograpy and keywords in the term value and the API will parse them. This
        can potentially cause inaccurate matches if the business name includes place
        names, however. For example, the "LA wine Company" might be found in a search
        for "wine+LA" where LA is intended to mean Louisiana. Therefore, where possible,
        use the searchloc + term combination.
      operationId: getSearch
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
      - in: header
        name: User-Agent
        description: User agent
      responses:
        200:
          description: OK
      tags:
      - Search
  /details:
    parameters:
      summary: Parameters Details
      description: Parameters details.
      operationId: parametersDetails
      x-api-path-slug: details-parameters
      responses:
        200:
          description: OK
      tags:
      - Details
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