# Demo App

[https://covid-19-tracker-ac218.web.app/]
Click the link to checkout the demo version of the running app hosted on Firebase cloud servers

## Project stack

This amazon clone has been created in js through and through. At the front end React has been used. Deployment has been done using firebase.

## [Frontend]

## Available Scripts

In the project directory, you can run:

### `npm install`

This command will load the required dependencies for the front end and backend. You need to run it in the main folder as well as inside the amazonclone/functions folder in the console.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

This will help you get started. Run this in the main folder to view frontend at the port 3000.

### `npm run build`

Use this command in the console to build the frontend. This same build will be used to host on the firebase server.

### `firebase init`

Use this command to get started with firebase for backend functionality.

Configure firestore, functions and hosting.

### `firebase deploy --only hosting`

This will deploy your front end. Use the url which you will see in the firebase console.

## Dependencies needed

### Line Chart->

(npm install --save react-chartjs-2 chart.js)

### @material-us/core

### react-leaflet (The Map)

### leaflet (Also the Map)

### react-chartjs-2 chart.js (graph chart chartjs)

### numeral (for formating numbers.. (currency, percentages, decimal places))

(npm i numeral)

## USe

-The dropdown can be used to view Coid 19 daily and total cases, recovered and deaths for each country.

-The same can be viewed automatically on selction on the map.

-Also, total cases are listed countrywise on the right hand side in the decreasing order of cases.

-Each cases, recovered and death individual tiles can be clicked to view the worldwide line graph trend over the past few days.
