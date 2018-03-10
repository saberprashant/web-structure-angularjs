# Web-Structure-angularjs

A boilerplate structure for web applications.

    M-MongoDB
    E-ExpressJS
    A-AngularJS
    N-NodeJS

### Features :

*  Register a new User
*  Login using email,username or mobile
*  Logout
*  Edit Profile
    ->Username
    ->Profile data(Name,Address)
    ->Add mobile number
    ->Upload profile picture
*  Email Verification
*  Mobile number verification
*  Reset Password using Email
*  Dual data validation (Both client and server side)
*  Dual password encryption 
    ->MD5 on client side to hide passwords in requests
    ->SHA512 and salt on server side to store in database
*  Shows login status on top
*  SPA design(Single Page Application)
*  Passport.js integeration ready with 
    >  Google Sign-In Integration  
    >  Facebook Sign-In Integration
*  Realtime Username Availability Check
*  Loading Screen Animations (Choose your favourite one,Easily configurable)
*  Database in MongoDB(JSON format)
*  Full application easily configurable and manageable
*  Bootstrap Enabled
*  Full Session Management capabilities
*  Multer integeration for file uploads    

  
## Getting Started

### Prerequisites

#### For running purposes

    -Node.js installed on the system
    -MongoDB installed on the system and configured
    -A Twilio Account SID,Token and Mobile Number for using mobile number verification
     (Get them by registering at their website https://www.twilio.com/)
    -A valid Email account and password for sending Emails for email verification
    -Google ClientId ,Api key
    (Get it by registering as developer from https://console.developers.google.com)
    -Facebook AppId
    (Get it by registering as developer from https://developers.facebook.com)

#### Following node package is required to be installed globally

* bower
```
npm install -g bower
```

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

   ##### Setting up application
        -Clone the project
        -Open cmd/terminal
        -Change current directory to project directory
        -Run command:
            >npm install
        -Change current directory to public
        -Run commands:
            >npm install
            >bower install 
    
        -Go to project directory > config and open config.js
            >Replace database path with your own database path.
            >Replace session database path for session database.
            >Add Email id,password to send email from.
            >Add Twilio account id,token and number to send message from.  
            >Change session keys suitably(any no. of random strings).

        -Go to project directory > public > scripts > app.js
            >Add google client Id and api key
            >Add facebook appId

   ##### Running the application
        -Open cmd/terminal 
            >mongod --dbpath="Directory of mongodb databases"
        -Open another cmd window/terminal
            >node serverstart.js
        -Open browser and in address bar type:
            localhost:1234

    Yay! the application is ready :)


## Built With

* [AngularJS](https://angularjs.org/) - The web framework used
* [NodeJS](https://nodejs.org/en/) - Platform used for creating and running server
* [ExpressJS](https://expressjs.com/) - The node.js framework used
* [MongoDB](https://www.mongodb.com/) - Used for creating and managing database 
* [Yeoman](http://yeoman.io/) - Used for running generators.
* [Angular-generator](https://github.com/yeoman/generator-angular) - Used for creating angular application base. 
* [Express-generator](https://www.npmjs.com/package/express-generator) - Used for creating base structure for nodejs application.  


## Authors

* **Prashant Jain**  
[Linkedin](https://www.linkedin.com/in/saberprashant/)


