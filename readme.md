###React Weather Application

###** (needs to be updated. Run locally for most recent demo)

--------------------------

1. First ```fork``` and ```star``` the project.
2. Run ```npm install``` to install all needed dependencies.
3. Navigate to [OpenWeatherMap's ](http://openweathermap.org/) and get a free API key. Then, create a file name ```.env``` in the project root and add the following line: ```API_KEY=yourkeyhere```. This will give you access to API_KEY as a global variable anywhere in the client. It allows you to use your API Key while keeping it secret from everyone else.
4. Get a key to access [Google Places API](https://developers.google.com/places/web-service/get-api-key) and replace `API_KEY` in `index.html` with access key you got from google.
5. If you don't have webpack installed on your machine, run ```npm install webpack -g```.
6. Open up two command prompts. In one, run ```webpack -w```. This lets webpack watch for changes to your files. After any saved changes, webpack automatically runs and updates your ```bundle.js``` file.
7. In the other command prompt run ```npm start``` or ```node server.js```. These commands do the same thing: Starting your server to host the web app.
8. Navigate to ```localhost:3000``` to see the app in action


Version notes:

Given more development time, later versions could include:

Language support – user can change language. To simplify development, only use languages available from the OpenWeatherMap API.
Location support – user can change location of forecast (free text typing + auto recognition of city by parsing restricted list of available cities).
Additional data – ability to show additional information, such as humidity and hourly temperatures.
More detailed forecasts.
Previous state restoration on initial load.
Ability to change location displayed.
User error messages.
Automatically refresh data every 15 minutes.
User Feedback/ Suggestion message.
