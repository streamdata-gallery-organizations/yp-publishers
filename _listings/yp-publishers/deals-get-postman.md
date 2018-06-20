{
  "info": {
    "name": "Yellow Pages API Get Coupons Near Location",
    "_postman_id": "eb5926ed-2bcb-494b-ad3f-e2a5a845899b",
    "description": "Get Coupons Near Location",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "b4b8aaa1-6f57-42a7-a742-42c3fbfcaf15",
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
          "id": "9107c17a-cb47-4d91-9726-e83c307fe904"
        }
      ]
    },
    {
      "id": "c59d297d-7a8d-4276-88a7-23c55a57e67f",
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
          "id": "52ac139b-8cb4-41ea-be32-41d2179d99c2"
        }
      ]
    }
  ]
}