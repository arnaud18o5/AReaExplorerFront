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

For the moment, the user has to allows Cross Origin Resource Sharing (CORS) on his Web browser, by installing an extension like [Allow CORS: Access-Control-Allow-Origin](https://mybrowseraddon.com/access-control-allow-origin.html) for example. The user needs to do this if he wants to be able to see the 3D objects of his items with Three.js. We are now working on a solution to avoid this.

The user needs to have an account on the database.

## Instructions

Click on this URL : https://arnaud18o5.github.io/AReaExplorerFront/

Click on "Login" if you have already an account or "Sign-Up" if you don't:
    In login modal : Enter your informations (username and password)
    In Sign-up modal : Create your informations (username and password)

Once connected the user can see a list of his items at the left of the screen. He can also create a new item by clicking on the "+" grey button at the top right of the list. 

How to create a new item :
    After clicking on the "+" grey button the user select the type of item he wants to create : 2D or 3D item. If he selects 2D item, he will have to fill a form with all the details of the item and the object of the item will be an image file (png, jpg...). If he selects 3D item, he will have to fill the same form but he will have to add GLTF file, BIN file and Texture Files for the 3D object.
    Then he just has to click on "Upload Item" button.
    If everything went well the item has been added to the database and the user can see it on the list at the left.

When the user click on an item in the list, the website will display all the information of the item at the center of the screen. He will be able to see the 3D item thanks to Three.js. The user can edit the informations of the item. He can also save the QR Code of the item by clicking on the button below this one.

The user is able to add a point of interest by filling a form at the bottom of the screen. The user can type the position of the point of interest but he can also click on the object to set the correct position of the point of interest.

When a point of interest is added to the database, the user can see it on the list of point of interest at the right of the item. He can see all the details of the point of interest.


## Next features

    * The possibility to edit the informations of a point of interest
    * The possibility to display the point of interest on the item
    * The possibility to set the location (lattitude and longitude) by clicking on a map
    * Display toasts messages when something happens
    * Add a home page to present the mobile application