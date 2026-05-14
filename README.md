# How to use this web application

unfortunately no live deployed link available.

clone the repo in your computer, and create a .env.local file in the client folder and then create a .env file in the server folder. and paste the code is given below.

***.env.local for front-end (client)***
```
VITE_IMAGE_UPLOAD_API_KEY=fdfb862b6ea6c28d6e01c4efd658ccbb
VITE_FIREBASE_API_KEY=AIzaSyDMmRsP-TXE77uq7mIBcM7P4nhNQUIpWP8
VITE_FIREBASE_AUTH_DOMAIN=college-management-web-a-2a487.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=college-management-web-a-2a487
VITE_FIREBASE_STORAGE_BUCKET=college-management-web-a-2a487.firebasestorage.app
VITE_FIREBASE_MESSAGING_SENDER_ID=754794960601
VITE_FIREBASE_APP_ID=1:754794960601:web:87ad53d3437e175e3c50c8
VITE_FIREBASE_MEASUREMENT_ID=G-SPG4220N74
```
***.env for server***
```
ACCESS_TOKEN_SECRET=47f43d06ec2f809deabbcc76b6fe9e807a5848ba18b7fd249821932560cb04a868ba64161f8bd0c9b7b36bd46e6803aaa42ecde7c6ab42dc4bfb31d3f8aebe7f
DB_PASS=4pP4aCyA6kBAcCWf
DB_USER=TUCMWA
SSLCZ_STORE_ID=ndc690488e0725b6
SSLCZ_STORE_PASS=ndc690488e0725b6@ssl
SSLCZ_VAl_API=https://sandbox.sslcommerz.com/validator/api/validationserverAPI.php
SERVER_URL=http://localhost:5000
CLIENT_URL=http://localhost:5173

```
**you can use your credentials.**
if my mongodb cloude cluster become pause, you can use offline uri for database ```mongodb://localhost:27017```

run command for client:

```$ bun run dev```

run command for server:

`$ bun start`

hope that everything will work fine. thank you.