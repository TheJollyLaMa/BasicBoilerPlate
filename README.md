# Skeleton Practice

## start a simple backend node server for practice
✅ initialize node:<br/>
```npm init```<br/>
✅ install basic middleware:<br/>
```npm install express ejs```<br/>
✅ install nodemon server in dev dependencies:<br/>
```npm install nodemon --save-dev```<br/>
✅ add start scripts to package.json:<br/>
```scripts": {"test": "test", "start": "node server.js","dev": "nodemon server.js"}```<br/>
✅ start dev nodemon server:<br/>
```npm run dev```<br/>
<br/>
## setup serverside index and error pages and routes with background image
✅ router files:<br/>
  ```/routes```<br/>
✅ view pages:<br/>
  ```/views```<br/>
<br/>
## setup favicon and public route
  #### ✅ add a favicon.ico file in this directory:<br/>
  ```/public/img/icons/favicon.ico```<br/>  
  #### ✅ add the link to the index.html head<br/>
  ```<link rel="icon" type="image/x-icon" href="../public/img/icons/favicon.ico" />```<br/>
  #### ✅ make the public route in index.js<br/>
  ```app.use('/public/index.html', express.static('public/index.html')); app.use('/public', publicRouter);```<br/>
  
