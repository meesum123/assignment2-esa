# ASSIGNMENT 2 (ESA)

microservices for an online shopping platform.

The platform has two microservices. The first microservice interacts with the user (assuming they have logged in and are valid users). The second microservice interacts with the people running the e-commerce site. They can add/update inventory as per the available stock.

## SETUP AND EXECUTION



Running the server

```
~assignment2-esa/user api>npm start
```

Output :

```
> api-try@1.0.0 start ~\assignment2-esa\user api
> nodemon server.js

[nodemon] 2.0.2
[nodemon] to restart at any time, enter `rs`
[nodemon] watching dir(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node server.js`
shopping cart RESTful API server started on: 4000

```

new term:

```
~assignment2-esa/product api>npm start
```
OUPUT: 

```
> product-api@1.0.0 start ~assignment2-esa\product api
> nodemon server.js

[nodemon] 2.0.2
[nodemon] to restart at any time, enter `rs`
[nodemon] watching dir(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node server.js`
Product RESTful API server started on: 3000
```



new term:

```
~assignment2-esa/>python userMicroservice.py
```


new term:

```
~assignment2-esa/>python productMicroservice.py
```
Note: the microservice.py files have their own instructions within the code. 




## Built With

* [Node.Js](https://nodejs.org/en/) - The web framework used
* [MongoDb Atlas](https://www.mongodb.com/cloud/atlas) - Database Management
* [Python](https://www.python.org/) - Microservice script


