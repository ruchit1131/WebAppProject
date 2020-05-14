# WebAppProject

Make sure you have node.js and npm installed

Open command prompt and navigate to the project folder using 'cd' command.
type 'npm install' and hit enter.
After the node_modules have been installed, type 'node server.js' to start the server.
Open 'localhost:3000' in your web browser and the website will be displayed to you.

This project has been made using html, css, javascript and node.js
You can create an account and then login to the website. After you login, you can search movies, A list of movies corresponding to your search will be displayed. Click on the movie you want, and you will see the poster and the Summary of the movie and also its cast.
mustache templates were used to display the list and the movie info.
The movie info was taken from an api omdbapi.com in a .json file.
jQuery was used to get the .json file from the api. The jQuery.js file is included in the /public/javascripts folder.
The mustache.js file is included in /public/javascripts.
mustach template is used to display the json file data we get from the api.
bcrypt was used to hash the password when the user registers.
ejs templating engine was used instead of the regular jade templating engine.
express - web application framework
passport was used for the authentication of the registered user.
