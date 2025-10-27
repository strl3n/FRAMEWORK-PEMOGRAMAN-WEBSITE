Buat folder backend, lalu install :
  - npm init -y
  - npm i -g nodemon
  - npm i bcrypt cookie-parser cors dotenv express jsonwebtoken mongoose
  - npm i @faker-js/faker --save-dev

Buat folder src

Install : mongodb (https://www.mongodb.com/try/download/community)
          mongodb compass (https://www.mongodb.com/try/download/compass)
Install mongodb polosan (jangan sekalian dengan mongodb compass, lalu install mongodb compass secara terpisah)

Pada VSCODE download plugin EchoAPI for VSCODE untuk testing API (alternatif lain bisa menggunakan POSTMAN)

Pada folder src, buatlah folder :
  - controllers
  - middlewares
  - models
  - routes
Dan sebuah file :
  - seeder.js

Buat database pada MoongoDB :
  - Database Name : kuliah_iso_movie
  - Collection Name : movie
Untuk mengambil connection string, klik kanan pada localhost:27017, pilih "Copy connection string"

Pada folder backend, buatlah file :
  - .env
Lalu codenya :
  DB_URL=mongodb://localhost:27017/kuliah_iso_movie (PASTIKAN NAMA DATABASE SAMA DENGAN DI MOONGODB)
