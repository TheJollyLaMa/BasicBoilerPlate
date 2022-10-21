# Skeleton Practice

## start a simple backend node server for practice
✅ initialize node:
"""npm init"""
✅ install basic middleware:
"""npm install express ejs"""
✅ install nodemon server in dev dependencies:
"""npm install nodemon --save-dev"""
✅ add start scripts to package.json:  
""""scripts": {
    "test": "test",
    "start": "node server.js",
    "dev": "nodemon server.js"
  }"""
✅ start dev nodemon server 
"""npm run dev"""

## setup serverside index and error pages and routes with background image
✅ router files:
  """/routes"""
✅ view pages:
  """/views"""
  
## setup favicon and public route
  
  ✅ ####add a favicon.ico file in this directory:
  """/public/img/icons/favicon.ico"""
  
  ✅ ####add the link to the index.html head
  """<link rel="icon" type="image/x-icon" href="../public/img/icons/favicon.ico" />"""
  
  ✅ ####make the public route in index.js
  """app.use('/public/index.html', express.static('public/index.html'));
app.use('/public', publicRouter);""""
