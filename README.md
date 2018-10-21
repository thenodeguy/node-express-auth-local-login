# node-express-auth-local-login

[![Greenkeeper badge](https://badges.greenkeeper.io/bjvickers/node-express-auth-local-login.svg)](https://greenkeeper.io/)

A basic and lean recipe for implementing username/password authentication in a 
node express server.

Includes a setup script which will create the 'local/users' table and insert a
single default user:

Username: admin  
Password: admin

These credentials should be used to test the username/authentication.

Requirements
-
You will need a running MongoDb daemon.

To install
-
npm install

To setup
-
node run-script setup

To run
-
sudo npm start

To test in a browser
-
http://localhost/
