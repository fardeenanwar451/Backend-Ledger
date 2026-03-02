# Package JSON
- package.json stores project metadata, stores dependencies
- It's like the brain of your project.

# Express 
- It is node.js framework used to create servers, handle routes, send responses, handle middlewares.

# App.js
- App js has 2 responsibilities
- 1. Create server instance
- 2. Configure middleware and routes
- App.js does not start the server

# Server.js
- Starts the server

* Why separate app.js and server.js?
- Big companies follow this
- Better testing, clean architecture, scalability

* require vs import
- Two systems in Node: 
- 1. CommonJS - require - module.exports
- 2. ES Modules - import - export

# Nodemon?
- Automatically restarts server
- Detects file changes
- Saves time

