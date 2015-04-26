Q
====

An extensible, customizable real-time queue system, built with Meteor.

** This is an alpha release. This queue is fully functional, but code will move around and features will be added over the next few months. Keep checking back for the most up to date. **

Documentation will be extended in the next few weeks. To start:

Quickstart
----------
For front end branding, edit `client/stylesheets/scss/_branding.scss`

Compile css with 
```sh 
  sass --watch client/stylesheets/scss:client/stylesheets/css
```

To edit copy, edit `lib/constants.js`

To configure login:
```sh
  cp private/config.json.template private/config.json
```
Edit `private/config.json`.

This will also contain the admin account username and password you'll use to login later.

Startup with `meteor`

Deploy with `meteor deploy <your domain name>.meteor.com`

Login as an Admin to grant yourself mentor/admin access. In the javascript console, type:
```js
Meteor.loginWithPassword("<your admin username>", "your admin password");
```
