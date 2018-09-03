This project is based on NodeJs and Angular4. The REST APIs are supported as JWT token based system.
User first need to login and get token, pass that token to authenticate other routes(APIs).

and the GUI is in Angular4. It has login screen as home screen. When user loggedIn ,it will redirect to page
where it display the number of locks belongs to loggedIn user and also display the number of users by their username
User can perform CRUD operation on locks and user, user dont have permission to view other locks.

How to start the app?

To start the app follow below step:

Extract the zip and go to the root directory, you will find the sampledb.sql file , first you need to import this
database into mysql and set the database credentials into config file "config/config.json" as below:

{
  "development": {
    "username": "db_user",
    "password": "db_password",
    "database": "db_name",
    "host": "127.0.0.1",
    "dialect": "mysql",
    "secret":"sjhjshfsghgshuewyuzxzxlkalks298483@283782skjauquwqt93892_)(shdjgs)"
  },
  "production": {
    "username": "db_user",
    "password": "db_password",
    "database": "database_production",
    "host": "127.0.0.1",
    "dialect": "mysql",
    "secret":"sjhjshfsghgshuewyuzxzxlkalks298483@283782skjauquwqt93892_)(shdjgs)"
  }
}

Open your terminal and go to the root directory of the project and run the following commands:

1. npm install
2. npm start

Open your brower,and enter the url : http://localhost:5000 and hit enter, it will launch the web app,
here you can register your self and test the app.

------------------------------XXXXXXXXXXXXXXXX-------------------
# node_test
