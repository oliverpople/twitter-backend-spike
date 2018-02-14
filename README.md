# react-backend

Boiler-plate example template when using using Node.js, Express.js and React. Created with node express-generator and create-react-app.  


### Getting Started
Checkout this repo, install dependencies, then start with the following:

```
> git clone https://github.com/oliverpople/react-backend.git
> cd react-backend
> npm install
```
Run back-end server:
```
> PORT=3001 npm start
```
Then in a new command line tab run the front-end:
```
> cd react-backend/client
> npm start
```

### FYI

This example is cover in David Ceddia's free [tutorial](https://daveceddia.com/create-react-app-express-backend/). However, I had to add a CORS middleware function to the node express server (routes/index.js) in order to load node data from a separate port.

### To Do's

1) Try and make the front and back end run concurrently.
2) Think about how they would run off the same server, as they would in production.
# twitter-backend-spike
