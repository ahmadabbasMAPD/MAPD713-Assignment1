
# Assignment1
This is a code snippet written in JavaScript that creates a RESTful API server using the `restify` library. The server listens on port `5000` and IP address `127.0.0.1`. It has two endpoints: `/products` and `/products/:id`. 

The `/products` endpoint returns all the products in the system when a GET request is made to it. The `/products/:id` endpoint returns a single product with the given ID when a GET request is made to it. If the product does not exist, it returns a 404 error.

The code also includes a POST request handler for creating new products. It validates that the `name` field is present in the request body before proceeding with creating the new product.

