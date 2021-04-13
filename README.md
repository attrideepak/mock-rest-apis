# mock-rest-apis
Mocking restful apis using JSON server. Mocking APIs using JSON server involves zero coding and requires minimal configuration.

Steps to mock:
1. Install JSON Server : npm install -g json-server
2. Create db.json file.
3. Run JSon Server : json-server --watch db.json

Sample db.json file.

{
  "cars": [
    {
      "brand": "Tata",
      "name": "Hexa",
      "variant": "Diesel",
      "type": "3",
      "id": 1,
      "features": {
        "id": 1,
        "transmission": "automatic",
        "seater": 7
      }
    },
    {
      "brand": "Tata",
      "name": "Nano",
      "variant": "Diesel",
      "type": "1",
      "id": 2,
      "commentId": 1
    },
    {
      "brand": "Maruti",
      "name": "Swift",
      "variant": "Petrol",
      "type": "1",
      "id": 3,
      "commentId": 1
    },
    {
      "brand": "Ford",
      "name": "Figo",
      "variant": "Petrol",
      "type": "1",
      "id": 4,
      "commentId": 1
    },
    {
      "brand": "Hyundai",
      "name": "i20",
      "variant": "Petrol",
      "type": "1",
      "id": 5,
      "commentId": 2
    },
    {
      "brand": "Hyundai",
      "name": "Accent",
      "variant": "Petrol",
      "type": "2",
      "id": 6,
      "commentId": 2
    },
    {
      "brand": "Honda",
      "name": "City",
      "variant": "Petrol",
      "type": "2",
      "id": 7
    },
    {
      "brand": "Honda",
      "name": "Accord",
      "variant": "Diesel",
      "type": "2",
      "id": 8
    },
    {
      "brand": "Kia",
      "name": "Celtos",
      "variant": "Diesel",
      "ype": "1",
      "id": 9
    },
    {
      "brand": "Kia",
      "name": "Carnival",
      "variant": "Petrol",
      "type": "3",
      "id": 10
    },
    {
      "brand": "Tata",
      "name": "Nexon",
      "variant": "Petrol",
      "type": "3",
      "id": 11
    },
    {
      "brand": "Maruti",
      "name": "Swift Dezire",
      "variant": "Petrol",
      "type": "2",
      "id": 12
    }
  ],
  "type": [
    {
      "id": 1,
      "body": "Hatchback"
    },
    {
      "id": 2,
      "body": "Sedan"
    },
    {
      "id": 3,
      "body": "Suv"
    }
  ],
  "comments": [
    {
      "id": 1,
      "userComments": "Good Car"
    },
    {
      "id": 2,
      "userComments": "Bad Car"
    }
  ]
}

