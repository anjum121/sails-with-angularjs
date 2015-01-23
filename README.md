# Bulding Realtime Web Application With Sails and Angularjs
Creating sails realtime web application in windows 7, I am assuming that you already have  [Node.js](http://nodejs.org/) install and running.

Goto your working folder in command prompt, i am using power shell but default windows command prompt will also works fine.
```javascript
mkdir sails-with-angularjs
```
cd /sails-with-angularjs and run below command 
```javascript
sails new app
```
 This would generate a message
```javascript
info: Created a new Sails app `app`!
warn: Could not create symbolic links in the newly generated `node_modules` folder
warn: (usually this is due to a permission issue on your filesystem)
warn: Before you run your new app, `cd` into the directory and run:
warn: $ npm install
```
as you can see it will give warning to run `npm install` into /sails-with-angularjs/app directory, once done npm install its time to run our server with below command.
```javascript
sails lift
```
Open your web browser and hit to http://localhost:1337/ if all goes well you will see brand new app default page from sails

