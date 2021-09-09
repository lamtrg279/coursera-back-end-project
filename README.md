# Coursera Back End Project

**In this project I built a server side program that allows users to operate REST API. Users can also upload images into the database. I also set up the server to use HTTPS and configure the certificate and private key for use with HTTPS and use Express application to use cors, passport, jsonwebtoken, facebook-oauth to perform local authentication on users and admins**

#### Routes

`Dishes`:

  - /dishes
  - /dishes/:dishId
  - /dishes/:dishId/comments
  - /dishes/:dishId/comments/:commentId


`Promotions`:

  - /promo
  - /promo/:promoId


`leaders`: 

  - /leaders
  - /leaders/:leadersId


`Users`:
  - /users
  - /users/login
  - /users/logout
  - /users/signup


`imageUpload`: 

  - /imageUpload


`favorites`:

  - /favorites
  - /favorites/:dishId


`Facebook oAuth`:

  - /index.html

--- This project also makes use of Facebook OAuth Authorization. In order to make it work please setup an App by going to https://developers.facebook.com/apps/ and register your app by following the instructions there and obtain your App ID and App Secret. Then Paste the App ID in public/index.html and both the ID and Secret in config.js.

*This project was developed from Coursera Back End course*
