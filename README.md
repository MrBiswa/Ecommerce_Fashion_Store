# Ecommerce_Fashion_Store

Its a ecommerce web application  based on node js and mongo db.

#Steps to run the application

Install Node js, mongodb and postman to your system.

a)Open server and install dependence for typing “npm install” and do the same in client frontend as well in dashboard to install the dependencies.

b) .env file is there in server folder and paste this variables 

PORT = 5000

MONGO_URI = “your mongo url”

NODE_ENV = development

JWT_SECRET = “your jwt secret”

PAYPAL_CLIENT_ID = “your PayPal client id”

c) type "node server.js" in server folder terminal to run the server.

d)then go to client frontend folder terminal and type "npm start",wait for sometime it will automatically run in localhost.

e) Open postman choose POST method and run http://localhost:5000/api/import/user then run http://localhost:5000/api/import/products after response two sample data they will already be in your database

j) Now you can see products by run http://localhost:5000/api/products Method is GET

To run admin site, go to dashboard folder terminal and type "npm start",wait for sometime it will automatically run in localhost.


For Admin login username- admin@example.com

Password-123456
