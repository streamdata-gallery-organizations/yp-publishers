---
swagger: "2.0"
x-collection-name: YP Publishers
x-complete: 0
info:
  title: Yellow Pages API Get Business Listing Reviews
  description: Get Business Listing Reviews
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