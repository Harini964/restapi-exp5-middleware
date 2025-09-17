
![WhatsApp Image 2025-09-13 at 16 30 03_50919614](https://github.com/user-attachments/assets/b29d36da-2a95-4dc0-a929-85116e9c8ddf)

API Test - POST Request to /api/data

The screenshot below demonstrates a successful POST request to the /api/data endpoint using Postman. The request body contains JSON data, which includes information about a product, such as its name, price, and stock status.

Request Body (POST):

{
  "product": "Smartphone",
  "price": 699,
  "inStock": true
}


Response:
The server successfully processes the data and returns a response with a confirmation message, along with the received data.

Response Body:

{
  "message": "Data received successfully!",
  "your_data": {
    "product": "Smartphone",
    "price": 699,
    "inStock": true
  }
}
