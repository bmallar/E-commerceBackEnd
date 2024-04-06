# E-commerceBackEnd
I created backend code for a e-commerce website using Node, Express, Postgres and Insomnia

### FILE Explanation 
First off everythings in the Develop folder, then theres a config folder, a db folder, a models folder, a routes folder with a api folder inside, a seeds folder and a node_modules folder. 
The config folder has a connection file that has dotenv and sequelize linked, the dotenv link allows me to sign into my database by hitting npm start and the sequelize link allows me to make a live server with a connecting port.
Next Is the database folder that had a sql file that drops or creates the existing database
After that is the models folder that contains js files with organized data 
Then we have the routes folder with a index.js file, this file grabs our api
Then inside my routes folder is api folder with a another index.js that links all our routes to the api, all of these files tells the data where to go.
Next is the seeds folder that has pre made data in sql files for our database
Lastly is the node_modules folder with our node downloads
The rest of the files are a .gitignore to stop unwanted files sent to git hub, a .env to hide my log in info and the json packages that have our node downloads 
The server.js file incorporates everything together

### Functionality
The server.js file makes everything go full circle.
It starts with importing express, which is our api. It also imports our routes, which is new data for our database. Then it imports our connection to our database.
Next is sets up our sever and uses sequelize to connect our models to the database


1. [My repo Link](https://github.com/bmallar/E-commerceBackEnd)
2. [My video link](https://drive.google.com/file/d/1OPpOjm2hPMHqZLjJN1ZbHXFElzgtJCa7/view)