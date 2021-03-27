# Reverse-Passportjs

In this assaignment we were tasked with reverse engineering and providing a walkthrough of the ocde itself. This authentication application utilizes `sequalize` and `passport.js`. Below will be a walkthrough of the functionality of the app itself and the responsibility of each file. 

## App Functionality

When running this App on your localhost- you are able to log in, and log out. 

* The root page `"/"` - the root page.

* The `/login` - log in here. 

* The `/members` page - you are taken to this page once you are signed up using the email & password you provided.

## The Walkthrough

### Application folders/files


#### Package.json

This file is used to list out the dependecies needed in your project. This hold numorous metadata about corresponds to the project. This Also makes it easier for developers to 