
************
Backend
************

Prerequisite

mysql  Ver 8.0.29
ubuntu0.20.04.3 
node v16.15.1

***********
Installing

Import de mysql table (with some examples)
mysql -u root -p test_API_DB < db.sql


Run:  npm install
edit in App.js:

  host: 'localhost',
  user: 'root',
  password: 'xxxxxxxx,
  
************  
Run: node app.js
Test in your broser  http://localhost:5002/notes

