# twitter-backend-spike

This code is an iteration of my [react-backend](https://github.com/oliverpople/react-backend) boiler-plate repo. The purpose of this project was to use React's fetch method to render the response of an Express.js GET request.  This response contains tweet data from Twitter's timeline API endpoint.

### Getting Started
Checkout this repo, install dependencies, then start with the following:

```
> git clone https://github.com/oliverpople/twitter-backend-spike.git
> cd twitter-backend-spike
> npm install
```
Run back-end server:
```
> PORT=3001 npm start
```
Then in a new command line tab run the front-end:
```
> cd twitter-backend-spike/client
> npm start
```
Visit [http://localhost:3000/](http://localhost:3000/) to view rendered tweets.

### Challenges

Enabling CORS:  To successfully authenticate my request to a remote server I had to enabled CORS. A found two solutions to this challenge 1) Requiring and running the ['cors'](https://www.npmjs.com/package/cors) node package in my express app.js, and 2) Specify the Headers I'd like to add my remote server request (also in app.js).  
