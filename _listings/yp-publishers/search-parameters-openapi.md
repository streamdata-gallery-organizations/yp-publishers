---
swagger: "2.0"
x-collection-name: YP Publishers
x-complete: 0
info:
  title: US Yellow Pages Parameters Search
  description: Parameters search.
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