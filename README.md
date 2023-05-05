Product Management Web Application
This is a simple web application that allows users to view a list of products, add new products, and delete existing products. It has a responsive front-end built using React, a back-end built using Node.js and Express.js, and uses MongoDB to store the product data. User authentication is implemented using JWT.

Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/Kandulanaveennaidu/Product-s-Task
Install dependencies for the back-end:
bash
Copy code
cd Product-s-Task/backend
npm install
Install dependencies for the front-end:
bash
Copy code
cd ../frontend
npm install
Start the back-end server:
bash
Copy code
cd ../backend
npm start
Start the front-end server:
bash
Copy code
cd ../frontend
npm start
Navigate to http://localhost:3000 in your web browser to view the application.
Usage
To use the application, you will need to create an account or log in if you already have one. Once logged in, you can view a list of products on the home page, add new products by clicking the "Add Product" button, and delete existing products by clicking the "Delete" button next to each product.

API Endpoints
The following RESTful API endpoints are available:

GET /api/products: Returns a list of all products.
POST /api/products: Adds a new product.
DELETE /api/products/:productId: Deletes the product with the specified ID.
Technologies Used
React
Node.js
Express.js
MongoDB
JWT
Contributors
Your Name (youremail@example.com)
Feel free to fork the repository and contribute to the project!
