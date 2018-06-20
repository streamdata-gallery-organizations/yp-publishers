{
  "info": {
    "name": "Yellow Pages API Get Business Listing Map",
    "_postman_id": "9351a6b8-02a7-4cf6-9dc2-19e58eb2a8df",
    "description": "Get Business Listing Map",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "b2ed4a3d-8013-44a4-8a1f-3ed90bd80657",
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
          "id": "afe855f4-fb9c-44c8-9b8a-dec5606e5693"
        }
      ]
    },
    {
      "id": "133d2302-8e20-4d1b-9804-be1909f2998e",
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
          "id": "73be200d-b4ff-48bc-9351-b6f7504e4b4c"
        }
      ]
    },
    {
      "id": "d26921a7-11e4-4988-93ff-f82ae7c04948",
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
          "id": "aeae7dfa-5828-41d0-85a8-841df56c3b80"
        }
      ]
    },
    {
      "id": "e4861d69-7e4f-4111-a9a0-03f382de1840",
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
          "id": "3f523e67-38c4-481c-9576-07cf7cf39250"
        }
      ]
    },
    {
      "id": "aae1491e-549a-470d-8c72-01559b361786",
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
          "id": "6afdb75b-4ecf-40d1-9ed2-59b0469fe90c"
        }
      ]
    },
    {
      "id": "a78ec52d-775e-4250-a1bf-d8fcca2c8ccd",
      "name": "get-business-listing-map",
      "request": {
        "url": "http://api2.yp.com/content/v1/search?format=%7B%7D&listingcount=%7B%7D&pagenum=%7B%7D&phonesearch=%7B%7D&radius=%7B%7D&searchloc=%7B%7D&shorturl=%7B%7D&sort=%7B%7D&term=%7B%7D&User-Agent=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get Business Listing Map"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "3a9e827e-0e96-4d82-aa41-b8c7d29a664b"
        }
      ]
    }
  ]
}