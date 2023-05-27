# MERN_Login_App
Created a MERN Stack Application for OTP Authentication


## Working with the Project

Download this project from above link. Create two configaration files into the project.
First in the client and second in the server.


In the Client Folder create .env file and put this code inside it.

.env
```
REACT_APP_SERVER_DOMAIN='<server_domain>' # example 'http://localhost:8080'
```


After that create a file in the Server Folder with the name config.js and put the below code inside it.

config.js
```
export default {
    JWT_SECRET : "<secret>",
    EMAIL: "steve.franecki@ethereal.email", // testing email & password
    PASSWORD : "sMf46xCzrvdrxvuagc",
    ATLAS_URI: "<MONGODB_ATLAS_URI>"
}
```

💻 Technologies
React
Express
Nodejs

⚙️ Install
After installing node and npm run the following commands to clone the repo and install all the dependencies that is used for this application.

$ git clone https://github.com/SandraKSathish/MERN_Login_App.git
$ cd MERN_Login_App
$ npm install
