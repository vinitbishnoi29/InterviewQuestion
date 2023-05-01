For updating the products please use the following steps:
1. Open Postman and create a new request.
2. Select "Post" as the HTTP method.
3. Enter "http://localhost:2000/products"
4. Go to the "Body" tab and select the "raw" radio button.
5. Select "JSON" from the dropdown menu next to the "raw" radio button.
6. Enter the payload in JSON format. For example:
{
  "products": [
    { "name": "Product A", "quantity": 5 },
    { "name": "Product B", "quantity": -2 },
    { "name": "Product C", "quantity": 10 }
  ]
}
