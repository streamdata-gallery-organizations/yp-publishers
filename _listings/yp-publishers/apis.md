---
name: YP Publishers
x-slug: yp-publishers
description: YP is a leading local marketing solutions provider in the US dedicated
  to helping local businesses and communities grow. Formerly AT&amp;T Interactive
  and AT&amp;T Advertising Solutions, YP launched in May 2012, bringing the two companies
  together with the mission of helping local businesses and communities grow.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
x-kinRank: "7"
x-alexaRank: "0"
tags: YP Publishers
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/apis.md
specificationVersion: "0.14"
apis:
- name: US Yellow Pages Parameters Listingmap
  x-api-slug: us-yellow-pages
  description: Parameters listingmap.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///listingmap
  tags: Listingmap
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/listingmap-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/listingmap-parameters-openapi.md
- name: US Yellow Pages Get Listingmap
  x-api-slug: us-yellow-pages
  description: Returns an URL for a graphical map for a specified business listing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///listingmap
  tags: Listingmap
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/listingmap-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/listingmap-get-openapi.md
- name: US Yellow Pages Parameters Search
  x-api-slug: us-yellow-pages
  description: Parameters search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///search
  tags: Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/search-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/search-parameters-openapi.md
- name: US Yellow Pages Get Search
  x-api-slug: us-yellow-pages
  description: Supports a number of specific use cases for finding a listing. The
    search request must include a searchloc value to set the geographic context for
    the search. The term value can include both name and category keywords. Note that
    if your implementation uses a single search box, you can combine geograpy and
    keywords in the term value and the API will parse them. This can potentially cause
    inaccurate matches if the business name includes place names, however. For example,
    the "LA wine Company" might be found in a search for "wine+LA" where LA is intended
    to mean Louisiana. Therefore, where possible, use the searchloc + term combination.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///search
  tags: Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/search-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/search-get-openapi.md
- name: US Yellow Pages Parameters Details
  x-api-slug: us-yellow-pages
  description: Parameters details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///details
  tags: Details
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/details-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/details-parameters-openapi.md
- name: US Yellow Pages Get Details
  x-api-slug: us-yellow-pages
  description: Returns all available data for a given business listing, including
    hours of operation, website URL, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///details
  tags: Details
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/details-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/details-get-openapi.md
- name: US Yellow Pages Parameters Reviews
  x-api-slug: us-yellow-pages
  description: Parameters reviews.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///reviews
  tags: Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/reviews-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/reviews-parameters-openapi.md
- name: US Yellow Pages Get Reviews
  x-api-slug: us-yellow-pages
  description: Returns all available user reviews for a given business listing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///reviews
  tags: Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/reviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/reviews-get-openapi.md
- name: US Yellow Pages Get Coupons
  x-api-slug: us-yellow-pages
  description: Returns coupons near the submitted location. Optionally, a term parameter
    can be submitted to restrict coupons to relevant categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///coupons
  tags: Coupons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/coupons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/coupons-get-openapi.md
- name: US Yellow Pages Get Deals
  x-api-slug: us-yellow-pages
  description: 'Returns Deal of the Day offers near the submitted location. Currently,
    four US Markets are supported: Los Angeles, Atlanta, Dallas and National. You
    can use specific zip codes within the three city markets, the market city or "national".
    This endpoint only supports JSON format response at this time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1///deals
  tags: Deals
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/deals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/deals-get-openapi.md
- name: US Yellow Pages
  x-api-slug: us-yellow-pages
  description: YP is a leading local marketing solutions provider in the US dedicated
    to helping local businesses and communities grow. Formerly AT&amp;T Interactive
    and AT&amp;T Advertising Solutions, YP launched in May 2012, bringing the two
    companies together with the mission of helping local businesses and communities
    grow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1/
  tags: YP Publishers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/openapi.md
- name: Yellow Pages API Get Business Listing Reviews
  x-api-slug: yellow-pages-api
  description: Get Business Listing Reviews
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1//coupons
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/coupons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/coupons-get-openapi.md
- name: Yellow Pages API Get Coupons Near Location
  x-api-slug: yellow-pages-api
  description: Get Coupons Near Location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1//deals
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/deals-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/deals-get-openapi.md
- name: Yellow Pages API Search Listings
  x-api-slug: yellow-pages-api
  description: Search Listings
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1//details
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/details-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/details-get-openapi.md
- name: 'Yellow Pages API '
  x-api-slug: yellow-pages-api
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1//listingmap
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/listingmap-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/listingmap-get-openapi.md
- name: Yellow Pages API Get Business Listing Details
  x-api-slug: yellow-pages-api
  description: Get Business Listing Details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1//reviews
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/reviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/reviews-get-openapi.md
- name: Yellow Pages API Get Business Listing Map
  x-api-slug: yellow-pages-api
  description: Get Business Listing Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1//search
  tags: ~
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/search-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/search-get-openapi.md
- name: Yellow Pages API
  x-api-slug: yellow-pages-api
  description: YP is a leading local marketing solutions provider in the US dedicated
    to helping local businesses and communities grow. Formerly AT&amp;T Interactive
    and AT&amp;T Advertising Solutions, YP launched in May 2012, bringing the two
    companies together with the mission of helping local businesses and communities
    grow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/yellow_pages_2013_00_logo_detail.png
  humanURL: https://yp.com
  baseURL: https://api2.yp.com//content/v1
  tags: YP Publishers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/yp-publishers/master/_listings/yp-publishers/openapi.md
x-common:
- type: x-case-studies
  url: http://resourcecenter.yp.com/casestudies
- type: x-contact-form
  url: https://publisher.yp.com/contact_us
- type: x-developer
  url: https://publisher.yp.com/
- type: x-twitter
  url: https://twitter.com/yellowapi
- type: x-privacy
  url: http://corporate.yp.com/about/privacy-policy
- type: x-terms-of-service
  url: http://www.yellowpages.com/about/legal/terms-conditions
- type: x-website
  url: https://yp.com
- type: x-website
  url: http://yp.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---