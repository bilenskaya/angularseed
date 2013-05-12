# AngularJS / Express / RequireJS / Passport - Seed

This is my seed Project. 
I use what I believe are good practices, and of course, with a bunch of personal preferences that may be changed. 
No Jade here :) Me no like.

## Core technologies used

- NodeJS
- Express Framework
- AngularJS
- RequireJS
- Passport

## Overview

This Seed provides users with RequireJS module loading, PassportJS registration / authentication and AngularJS as the client framework.

Upon registration, the application sends a confirmation e-mail. As for now, I'm not doing anything with it, but I plan to add more features sometime soon (Tests are a must).

## Directory Structure
    
	app.js              	--> web server
    package.json        	--> package dependencies
    app/             		--> main app
  		api/				--> api for model manipulation
      	css/              	--> css files
      	helpers/			--> generic helpers (I added an encryption helper)
      	js/               	--> javascript files
      		components/		--> logger component
        	controllers/	--> application controllers      	
        	app.js          --> app module
        	main.js 		--> main application bootstrap
        	routes.js 		--> client side routing definition
    	lib/            	--> angular and 3rd party JavaScript libraries
    	models/				--> mongoose models
    	views/				--> main view and partials
	config/					--> application config folder
		app(.)-strings.js 	--> re-usable strings used by application
		config.js 			--> app default configs (db name, etc)
		conf(.)-routes.js 	--> routing passing point
		mailer.js 			--> mailer module
		passport.js 		--> passportjs configuration
		routes.js 			--> routes's implementation

Hope you like it,
Tiago
