# ARea Explorer Web Frontend

This is the Web Frontend side of the app ARea Explorer. The application also
contains [Backend](https://github.com/Lauri92/arvr-backend)
and [Android mobile app](https://github.com/TuomasB73/AR_VR_Map_App). Be sure to check out those
repositories to get a better idea how this application functions as a whole. This README will only
cover areas related to the Web Frontend application.

## General informations

This is a React JS application using Bootstrap for the style and Three.js for displaying and using the 3D objects.
This website allows the user to add his own 3D items to the database. He can also edit and delete them. This application makes the user able to add points of interest on his items.
The application is hosted on GitHub pages : https://arnaud18o5.github.io/AReaExplorerFront/.


## Prerequisites

For the moment, the user has to allows Cross Origin Resource Sharing (CORS) on his Web browser, by installing an extension like "Allow CORS: Access-Control-Allow-Origin" (https://mybrowseraddon.com/access-control-allow-origin.html) for example. The user needs to do this if he wants to be able to see the 3D objects of his items with Three.js. We are now working on a solution to avoid this.

The user needs to have an account on the database.

## Instructions

    *Click on this URL : https://arnaud18o5.github.io/AReaExplorerFront/
    *Click on "Login" if you have already an account or "Sign-Up" if you don't:

   <img src="/Login.jpg" width="200" />
    


## Instructions

1. Login and registration

   <img src="https://user-images.githubusercontent.com/64253189/146197114-63e1a4d1-7b50-4376-b655-c4d25053e9c8.jpg" width="200" />
   <img src="https://user-images.githubusercontent.com/64253189/146197216-5c2c8202-a801-4ba8-84dd-0172a3b65efd.jpg" width="200" />
   
   Login or register in the app first. See the credential requirements by tapping the info button.  
   
2. Home screen

   <img src="https://user-images.githubusercontent.com/64253189/146197571-31fc3393-f897-4316-9ca6-2dcf5a4c5e68.jpg" width="200" />
   
   This is the home screen. There are two main features, QR code scanning and saved maps screen.
   
3. QR code scanning

   <img src="https://user-images.githubusercontent.com/64253189/146197999-88fa4423-de05-40a9-8467-9bf4e39eec3d.jpg" width="200" />
   
   On the home screen press the "Read QR code" button, point the camera at a QR code that references an AR map and then press "Open in AR" button in the dialog that appears.
   
4. Finding a plane/level in the AR mode and placing the 3D map

   <img src="https://user-images.githubusercontent.com/64253189/146198760-6dc229ab-0b9b-466b-ad03-a32852cc568b.jpg" width="200" />
   
   Find a plane/level in the AR mode by moving the phone and pointing the camera at different surfaces. When a grid of white dots appears, a plane/level is recognized. Now press the "Place 3D map" button and the map will be loaded and displayed in a moment.
   
5. Add points of interest on the map

   <img src="https://user-images.githubusercontent.com/64253189/146200188-a23f145b-d74d-4d65-b48f-4062a68f17d6.jpg" width="200" />
   <img src="https://user-images.githubusercontent.com/64253189/146211889-2bd0ad7a-d80e-4736-b68e-8a6da170fcf4.jpg" width="200" />
   
   Swipe from the left edge of the screen to open the points of interest menu. Here you can see all the points of interest for the map. Tap on the items that you want to see on the map and then close the menu. Now you can see those points of interest on the map with a text and/or logo. Tap them to see details about them.
   
6. Interaction and features

   <img src="https://user-images.githubusercontent.com/64253189/146201445-624105bd-bb41-4db9-8f31-02fcc1c25632.jpg" width="200" />
   
   At the top of the screen there is a row of buttons for different features. Press the location icon to see your own estimated location on the map. Press the arrow icon to resize the points of interest.
   
   You can move and zoom the map simply with the touchscreen, but there are also motion gesture interactions available for zooming the map and removing all points of interest from the map. See instructions for the motion gestures by tapping the info button, and disable or enable the gesture controls with the switch on the top corner of the screen.
   
   You can also move yourself around the model and view it closer or further away. Lastly, you can press the heart icon to save the map for yourself on the app.
   
7. Saved maps screen and map location

   <img src="https://user-images.githubusercontent.com/64253189/146203098-54aafcd0-d17e-4f1c-8bee-c93da3fef76e.jpg" width="200" />
   
   On the home screen press the "My saved maps" button to see all your saved maps. You can search from them by the name and tap on them to see details. Press the "Show location on map" button on the details dialog to see the real location of the 3D map model on a regular map view. You can also open the AR mode from the details dialog as well as deleting it from your saved maps.