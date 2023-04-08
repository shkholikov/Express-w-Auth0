# Express-w-Auth0 🔐
### Description
Used Node.js, Express, Pug, and CSS to create a web application that renders a stylish user interface with dynamic data by communicating with an API.

### Authentication part
Also used Passport.js with Auth0 to manage user authentication and protect routes of a client that consumes an API. The client is server-side rendered using Pug templates styled with CSS.

### Connect to your tenant
Take a look at the .env.example in the source code. You need to set up a connection to your Auth0 Tenant. Check this [guide](https://auth0.com/docs/quickstart/webapp/express/01-login) out to set up Auth0 Tenant. 

### How to test? 
Clone this project using the following code:
```
git clone https://github.com/shkholikov/Express-w-Auth0.git
```
Install project dependencies: 
```
npm i
```
Open terminal and run the server: 
```
npm run dev
```
Open another terminal and run the ui:
```
npm run ui
```

### Issues
Feel free to create an issue in the issues section, if something wrong in this application.