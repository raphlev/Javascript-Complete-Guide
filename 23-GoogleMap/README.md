#  Project Setup
https://www.udemy.com/course/javascript-the-complete-guide-2020-beginner-advanced/learn/lecture/16440754#overview

Build google map service app.
Go to https://console.cloud.google.com/google/maps-apis/
Create new google project
- Enable Geocode API
- Enable MAP APi
- Enable Place API ??
Replace API Key in location.js (geocode) + index.html (map api) + my-place/index.html (map api): create API Key from above project
- https://console.cloud.google.com/google/maps-apis/credentials?folder=&organizationId=&project=optimal-plate-314414

# Install

by default dist folder contains html+css code, javascript is in src folder
using npm run build:dev, wenpack will use dev server and load the scripts without copy them to scripts folder
using npm run build, webbpack will copy and transformed java script files inside dist/assets/scripts
using npm run build:prod, webbpack will copy and transformed and reduced and renamed java script files inside dist/assets/scripts, to use them update script tags in both index.html with new names before deploying the app
