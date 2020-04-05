# Budget Tracker

Repository: https://github.com/aarkitekkt/budget

Deployed: https://aarkitekkt-budget.herokuapp.com/

## Overview
​
The purpose of this application it to take an existing budget app and make it work offline.

### Gallery

Online:
![Online](/public/assets/screengrabs/online.png "Online")

Offline:
![Offline](/public/assets/screengrabs/offline.png "Offline")
​
### Description

Given an existing working project, the task is to add code so that the site may be used offline.  When online, transaction data is saved the Mongo Database but this is not possible when offline.  IndexedDB is used to temporarily save any submitted transactions locally while offline until the connection is restored and that data can be posted to the database.  A service worker was added to cache the necessary files to run the app.  These files are saved in the static cache and can be served to load the page even when not online.

### Tech and Features Used
​
* MongoDB
* Mongoose
* Express npm
* Morgan npm
* Heroku
* Node JS
* IndexedDB
* Compression
* Lite-Server
​

