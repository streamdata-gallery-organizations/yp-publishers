{
  "info": {
    "name": "Yellow Pages API ",
    "_postman_id": "a10ae6ac-a84b-41b2-869b-1b09fdf40fde",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "10c78a38-89bd-40ab-b547-7d8127412c6e",
      "name": "get-business-listing-reviews",
      "request": {
        "url": "http://api2.yp.com/content/v1/coupons?format=%7B%7D&searchloc=%7B%7D&term=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get Business Listing Reviews"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "7556e80d-c5ff-4897-ab5e-9c8f1ff5206c"
        }
      ]
    },
    {
      "id": "9b888b8b-90c3-4237-af02-c4daec8ca665",
      "name": "get-coupons-near-location",
      "request": {
        "url": "http://api2.yp.com/content/v1/deals?searchloc=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get Coupons Near Location"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ea729124-6653-42ca-af69-75ace842d89a"
        }
      ]
    },
    {
      "id": "c50fa242-68a7-45fe-9e9c-a2292c2bed05",
      "name": "search-listings",
      "request": {
        "url": "http://api2.yp.com/content/v1/details?format=%7B%7D&listingid=%7B%7D&User-Agent=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Search Listings"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "cbb748c7-d67f-4540-a27d-adf6560571d7"
        }
      ]
    },
    {
      "id": "1bd90088-4f03-4d8c-bccc-52ff06257387",
      "name": "Listingmap_GET",
      "request": {
        "url": "http://api2.yp.com/content/v1/listingmap?image_format=%7B%7D&listingid=%7B%7D&pan_horizontal=%7B%7D&pan_vertical=%7B%7D&pixel_height=%7B%7D&pixel_width=%7B%7D&zoom=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": ""
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "c1d27b91-64fa-4816-9038-63067056e2d4"
        }
      ]
    }
  ]
}