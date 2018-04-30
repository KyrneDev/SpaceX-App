### About
This was my project for my SpaceX internship application. It lists all of the ground stations that SpaceX satellites use

---

### Instructions
1. `git clone https://github.com/CDK2020/SpaceX-app.git`
2. `cd` into the `spacex-app` directory
3. Unzip the `img.zip` folder
4. `npm install`
5. `node server`
6. The server should now be running locally on port 3000. Give it a few seconds to download and parse the data then navigate to [http://localhost:3000/](http://localhost:3000/)

---

### Libraries used:
* [Express](https://www.npmjs.com/package/express) - NodeJS Web Server.
* [Request](https://www.npmjs.com/package/request) - Allows for easier HTTP requests.
* [Socket.io](https://www.npmjs.com/package/socket.io) - Websocket library to transfer data between the NodeJS web server and the client web page
* [xml2js](https://www.npmjs.com/package/xml2js) - Parses the XML retrieved from the SSC into a javascript object. 
* [Google Maps](https://developers.google.com/maps/)
