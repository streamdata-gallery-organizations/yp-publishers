{
  "info": {
    "name": "Yellow Pages API Get Business Listing Details",
    "_postman_id": "fbc5d687-f0c3-4a54-9a2b-a7bd461e68a7",
    "description": "Get Business Listing Details",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "c4b4c675-52e7-44b6-9d60-614d37ab8925",
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
          "id": "b1b636b0-ed6e-447e-b6c4-ebaf3a80c9c3"
        }
      ]
    },
    {
      "id": "599d00ce-0625-4845-9dd2-66f98dff98cd",
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
          "id": "90206fab-449a-44a7-9e25-60d9d93fbf69"
        }
      ]
    },
    {
      "id": "fba71495-1a72-4d2f-bdf8-dea929aa3ea6",
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
          "id": "89862c7b-5483-4c14-ac8a-22961840084b"
        }
      ]
    },
    {
      "id": "837d194e-de38-4f07-abb0-60aab8574071",
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
          "id": "9ca86ce3-cda7-4273-97fe-701f6fb88d4c"
        }
      ]
    },
    {
      "id": "34161f20-6dbb-4a37-9726-82708c5d40cf",
      "name": "get-business-listing-details",
      "request": {
        "url": "http://api2.yp.com/content/v1/reviews?format=%7B%7D&listingid=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get Business Listing Details"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "cfbebc85-81cf-4702-a1ff-d0da563822f4"
        }
      ]
    }
  ]
}