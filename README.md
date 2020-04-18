# twitter-data
A simple Twitter Data viewer that uses Node.js, React.js and Redis.

There are two files that need to be run. 
1. `worker.js` fetches the tweets and publishes them to Redis.
2.  `index.js` handles HTTP requests and sends new tweets to users using Socket.io.

npm install in root folder

 If you make sure you have set the appropriate environment variables, and then run node worker.js in one terminal, and node index.js in another, and visit http://localhost:5000/, you should see your Twitter Data