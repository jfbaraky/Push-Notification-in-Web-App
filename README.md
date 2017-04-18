# Push Notifications in WebApp

Implementation of [Push Notifications codelab](https://developers.google.com/web/fundamentals/getting-started/push-notifications/?hl=en), an introduction to using Push Notification in Web Apps.

## How to Setup

First you need:

* [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb)
* Chrome 52 or above

After you clone this code, open the Web Server and set the folder to "app" folder. You will recieve the Web Server URL that you will need to see the updates, but first, check the box "Automatically show index.html" and don't close this window.

Open the Dev-Tools in Chrome (Ctrl+Shift+J), go to the Application panel, click the Service Workers tab and check the Update on Reload checkbox. This way, you have the guarantee of update in the refresh of the page.

You also need to set the Public key of your server. You can do this using the [Push Companion](https://web-push-codelab.appspot.com/) site.

Copy the Public Key (never the Private Key) and open the scripts/main.js. Update the applicationServerPublicKey:
```
const applicationServerPublicKey = '<You need to change this value (keep quotation marks)>';
```

Now you need to register with the button and allow the notifications in the Chrome. You can send push messages also using the [Push Companion](https://web-push-codelab.appspot.com/).

## Built with

* [WebStorm 2017.1.1](https://www.jetbrains.com/webstorm/)

## Also see

* [Sample Code](https://github.com/GoogleChrome/push-notifications.git)