
# CRUD
I'm using Nodejs, Express and Mongodb to create server for a product



## Usage/Examples


npm install express

const express = require('express')

npm install mongoose

const mongoose = require('mongoose')

npm install postman

npm install gitbash

mpm install nodemon

## Tech Stack

**Client:** Insomnia

**Server:** Node, Express, MongoDB

## Support

For support, email olalereb688@gmail.com.

## API Reference

#### Create product

```http
  POST: http://localhost:3000/products
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| ` name` | `string` | "product name"|
| ` quantity` | `string` |"product quantity" |
| ` price` | `string` |"product price" |
| ` image` | `string` |"product image" |


#### Get product

```http
  GET: http://localhost:3000/products
```
#### Get a product

```http
GET http://localhost:3000/products/${id}
```


#### Update a product
```http
PUT: http://localhost:3000/products/${id}
```


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| ` name` | `string` | "product name"|
| ` quantity` | `string` |  "product quantity" |
| ` price` | `string` |"product price" |
| ` image` | `string` |"product image" |



#### Delete a product
```http
 DELETE: http://localhost:3000/products/${id}
```



## Documentation

[Documentation](http://localhost:3000/products)

