CRUD 

1. npm install 
2. Config.json - config for Sequilize and PostgreSQL
3. Migrations - " npx sequelize db:migrate;npx sequelize-cli db:seed:all "   
4. Start server - node app.js
5. app.js - Server that accepts requests: 
   get - /show - shows all users                             
   get - /user/:id - shows the user by ID
   put - /update - edits a user by id (in POSTMAN the "body" menu, select the "raw" type and next to the "JSON" type and enter the data as shown in the example 
   {
    "id": "1",
    "name": "bob"
   })
   post - /create  - create (in POSTMAN the "body" menu, select the "raw" type and next to the "JSON" type and enter the data as shown in the example 
   {
    "name":"bob"
   })
   delete - /delete/:id - deletes user by ID
   
