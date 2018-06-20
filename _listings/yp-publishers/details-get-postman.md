{
  "info": {
    "name": "Yellow Pages API Search Listings",
    "_postman_id": "228f359a-e88c-4a5a-a5f7-db2b7d347da9",
    "description": "Search Listings",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "ad14d902-ab11-47d0-9543-6ff856940009",
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
          "id": "e3e4628d-f606-415e-8699-9c170b6f5109"
        }
      ]
    },
    {
      "id": "43557699-163f-4ab8-ab09-011f8e0f7fe7",
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
          "id": "0f36d71c-96bd-4eca-b003-449663cc3699"
        }
      ]
    },
    {
      "id": "cdcea6b1-c088-4da6-8cb4-daf614134d8b",
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
          "id": "ae1b5548-6b18-46b3-bc4c-679ae76208d4"
        }
      ]
    }
  ]
}