# node-js-fetch-data-from-mongodb-using-mongoose
To fetch data from MongoDB using mongoose

########################################################

Step 1 - Create Node Express js App
Execute the following command on terminal to create node js app:
mkdir my-app
cd my-app
npm init -y

Step 2 - Install express flash ejs body-parser mongoose Modules
Execute the following command on the terminal to express flash ejs body-parser mysql dependencies :
npm install -g express-generator
npx express --view=ejs
npm install
npm install express-flash --save
npm install express-session --save
npm install body-parser --save
npm install mongoose

Step 3 – Connect App to MongoDB
Creating database.js file into the app root directory and adding the code into it & connecting the app to the mongodb database

Step 4 – Create Model
Creating Models directory and inside that directory creating userModel.js file

Step 5 – Create Routes
Creating routes, in the routes directory and open users.js route file

Step 6 – Create HTML Table and Display List
Creating html form for display list from mongodb database, So in the views directory, creating list.ejs file inside it

Step 7 – Import Modules in App.js
Importing express flash session body-parser mongoose dependencies in app.js

Step 8 – Start App Server
Use the following command to start node js app server:
npm start

"after run this command open your browser and hit" 

http://127.0.0.1:3000/list
