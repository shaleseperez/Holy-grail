# Holy-grail
Full stack application that displays the Holy Grail layout

### How to Run
* Download the zip and extract the files (Or fork the repository and fetch the files)
* Open the terminal and navigate to the root folder. Run `npm install` to install the dependencies.
* Next run the following commands `docker run -p 6379:6379 –name some-redis -d redis` and then `npm install redis` to install redis. 
* Finally run `node index.js` to start the server.
* Open http://localhost:3000 in your browser to see the holy grail layout.
* Click on the + or - sign in any section and the values will update across the components and on the server. 
