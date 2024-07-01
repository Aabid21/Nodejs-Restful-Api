*Setup And Run Nodejs Application

*Clone the repository
*Install dependencies:

 
In terminal Command npm install

*Set up MySQL database using XAMPP:
    Start XAMPP and activate the MySQL service
    Open phpMyAdmin and create a new database `nodejs_restful_api`
    Create the `users` and `roles` tables using the provided SQL scripts

*Update the database configuration in `config/database.js`:


*Run the application:

   
    node app.js
   

API Endpoints

Users

- **Create a user:** `POST /api/users`
- **Get all users:** `GET /api/users`
- **Get a user by ID:** `GET /api/users/:id`
- **Update a user:** `PUT /api/users/:id`
- **Delete a user:** `DELETE /api/users/:id`

Roles

- **Create a role:** `POST /api/roles`
- **Get all roles:** `GET /api/roles`
- **Get a role by ID:** `GET /api/roles/:id`
- **Update a role:** `PUT /api/roles/:id`
- **Delete a role:** `DELETE /api/roles/:id`

Testing

You can test the API endpoints using Postman or Curl.


