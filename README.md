# Abgabe_5_Heiland

# File structure:

On the first level are the HTML-files and the start.js which runs all server
functions in order to run the websites. In the public folder are different 
JavaScript files for the calculation and filling of the websites.

________________________
# How to start the server:

Open your command interface and navigate to the folder the files are saved in.
You need to install "body-parser", "mongodb", "express", "jquery" (npm install...).
To start the server enter npm install when you navigated the above metioned folder
and enter "npm install". Enter "http://localhost:3000/" in your browser.
To stop the server press CTRL+C then J and enter.

______________
# How the pages work:

On the main page are all bus stations in Münster an an OpenStreetMap. There are
also two tables that can show the departures of a station chosen from the map
and the next stations chosen from the database. The database contains all
points from the server. To show the point click "Database Content". Then choose
one of the radiobuttons and click "start Calculation" to see the closest stations.

On the second page you can add locations to the database. It's possible through
geocoding, your browser locations and adding a marker in the map. By clicking 
"Database Content" you can show the points from the server. Choose one or more
to delete them from the server. Choose one, click "Update one set of coordinates"
and enter coordinates in the format: lon (e.g. 7.618) , lat (e.g. 51.585). 
By clicking "Submit" the new coordinates are updated in the object.
