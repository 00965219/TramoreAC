# TramoreAC
Enterprise Web Development Project SPA Application

#Assignment 1 - AngularJS app.

Name: Clodagh O'Mara

###Overview.
This application website has been created for a running club. The idea is to have a site where club members can join and view information specifically tailored for them. The application website provides users with the ability to register and login to view club specific information.

Once logged in the user has the ability to view and edit their profile. They can also add posts to the club blog and enter comments on other user’s posts. The application also provides the users with a list of upcoming running fixtures which they can view or delete.

A catalogue listing club gear available to members is also available to the user to view. They can search by product/brand and then click on a specific product to view it in more detail if they wish.

The objective of this web application was to create a SPA application using the Angular JS MVC architectural design framework. I set out to use the key concepts learned in class and through the lab tutorials for Angular JS; Data-Binding, DOM / View updates based on model, Modular Architecture for the DOM, controllers and services. 

 . . . . . List of user features (excluding user registration and authentication) . . . . 
 
 + Hash Based Routing that allow the SPA application appear like a tradtional website to users.
 + User Home page with club details and useful links 
 + Editable user profile 
 + An editable list of club members
 + An editable list of upcoming club fixtures
 + Access to the club blog that allows members to post links and comment on other posts
 + Access to the club kit cataogue that show a list of all kit available and allows users to view each item listed in more detail.
 + The ability to register for the club newsletter.


###Installation requirements.

+ AngularJS 1.x
+ Bootstrap 3
+ $http server
+ jquery-2.1.3
+ Node JS
+ Sublime Text Editor

Download the zip file 'Project EWD.zip' which contains all of the application files within the appropriate folder structure.

The application can be viewed by launching the webserver in the root 'Project EWD' directory. Once the webserver has been launched the applicaiton can be viewed using the following address in browser 'http://localhost:8080/tramoreacApp/#/tramoreac'. The login username 'Clodagh' and password 'clodagh1' can be used to login.

+ There are no non standard software installations required to launch the application. 
+ There is no environment setup required borforehand.


###Data Model Design.

TramoreAC applicaiton Data Model.

![][image1]


###App Design.

TramoreAC applicaiton design model.

![][image2]

###UI Design.

Please open the document 'TramoreAC UI Design.docx' in the repository to view all of the User Interface design images.


###Routing.

List of each route supported and the associated view

+ /login - Login page for Tramore AC Club
+ /logout - Logout of the Tramore AC Club sit 
+ /main  - Login welcome home page displayed once user has logged in.               
+ /myhome - Link to user welcome home page 
+ /register - User registration page if they are not a member (registered)
+ /TramoreAC - Launch page for site	
+ /members  - A list of Senior club members
+ /fixtures - A list of upcoming running fixtures
+ /myprofile - Logged in user profile
+ /registersuccess - Confirmation of successful user registration
+ /myposts' - User Blog for viewing and adding posts
+ /posts/:post_id/comments' - Page for commenting on posts that have been added
+ /kits - List view of the club kit catalogue
+ /kits/:kitId - Detail view of a specific kit catalogue item


###Extra features

+ User registration and user authentication and login featuers have been added to the application.

The user registration has been created using an angular JS form and app controller and directive. The app controller created is 'RegisterCtrl' which if the registration form has been filled in validly will allow display the successful registration page to the user.

The user login has been created using an angular JS form and app controller. The app controller created is 'LoginCtrl' which if the registration form has been filled in validly will bring the user to the club homepage. If they do not fill in the form correctly the form controller will display error messages to the user such as 'username is too short' based on the errors that I have created in the error codes and messages.

###Independent learning.

As part of my research I researched angular forms and how I could incorporate them into my application and registration processes.

[image1]: ./TramoreACModelView.jpg
[image2]: ./TramoreACDesignModel.jpg
[image3]: ./TramoreACMainPage.jpg

# Assignment 2 UPdate:

##Main Features:
+ Home Page (News and useful links)
+	Profile (maintain your profile)
+	Members (Maintain Members)
+	Posts (Blog articles posted by members related to running)
+	Node JS javascript runtime server
+	Express Server
+	Mongolab Database and Mongoose library used for communicating with the MongoDB datastore.
+	API’s integrated Angular JS SPA client app that is integrated with a web API server.
+	API’s (GET, POST, PUT & DELETE implemented)

##Non- Standard Technical Features
+	Headers and Footers are ‘Include’ pages.
+	Navigations bars are implemented as ‘Include’ pages.
+	Used $locationProvider from html5 to simplify the URL’s and remove the #.

##HIGH LEVEL STRUCTURE
+ API - Web api/routing scripts folder
+ Config - Express apps configuration scripts folder
+ Node modules
+ Public - Public web resources folder
+ Package.json - application package description file
+ Routes.js
+ Server.js - Base Application Script for my express application

###Installation requirements.

+ AngularJS 1.x
+ Bootstrap 3
+ jquery-2.1.3
+ Node JS
+ Express
+ MongoDB
+ Mongoose
+ Sublime Text Editor

Download the zip file 'Assignment2.zip' which contains a folder called 'TramoreAC2' that has all of the application files within the appropriate folder structure.

The application can be viewed by launching the appliction by runing server.js using node in the root applicaiton folder 'TramoreAC2'.
Once the express webserver and mongoDB connection has been establised upon luanch the applicaiton can be viewed using the following address in browser 'http://localhost:4000/myhome'. 

+ It is required that the applications above be installed and running successfully in order to launch this application successfully.

###App Design.

TramoreAC applicaiton design model.

![][image4]

Demo Presentation - See Assignment2_App Presentation.pptx
