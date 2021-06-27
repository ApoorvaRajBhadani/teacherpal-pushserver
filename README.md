# Smart O'Class Express Server
Taking and managing attendance in online classes made easy with Chrome Extensions

Demo link - https://www.youtube.com/watch?v=74c9yu5rTWc

Steps to install -

$ npm install express web-push body-parser express-static

then find vapid keys by 
$ ./node_modules/.bin/web-push generate-vapid-keys

it will output something like this

Public Key:
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

Private Key:
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

=======================================

we will need these keys to further setup our chrome extension and server

On line 4 of index.js enter the publicVapidKey
On line 5 of indes.js enter the privateVapidKey

run the server with
$ node index.js

Link to Django server https://github.com/sahilss1499/smart-o-class

Link to Host chrome extension https://github.com/ApoorvaRajBhadani/smartoclass-host

Link to Attendee chrome extension https://github.com/ApoorvaRajBhadani/smartoclass-attendee# teacherpal-pushserver
