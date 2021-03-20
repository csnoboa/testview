# TestView-Frontend
The frontend is written in Flutter

You can access the site: https://csnoboa.github.io/testview_site/#/

The site is running the frontend and is connecting to the backend in http://127.0.0.1:5000/, so if you want to do it this way, you must let your backend in this URL!

Or, you can install flutter and build an app or a website:

# 0- Install Flutter
You can install Flutter in: https://flutter.dev/

# 1- Change the URL of the backend:

Change the variable "urlBackend" in: 
    lib\resources\config.dart

The default is "http://127.0.0.1:5000/api".

# 2- Run the project!
 
    flutter run -d chrome       to run in Chrome
or
    flutter run -d edge         to run in Edge
