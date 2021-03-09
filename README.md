# Zipcodes_Database_Project

#RESTful DB

#We write a Python Script, rest_web.py that:
#Hosts a web server on port 5000
#Has 2 pages: /search and /update
#/search queries an SQL DB and prints out the row data
#/update updates an SQL DB row

#Python Script
#Launches web server on port 5000.
#Queries the DB and returns information.
#Updates the DB.
#Uses XML or JSON packed messages to transport data.

#/search
#Search allows the user to search the DB by zip code:
#Serves a web page that at minimum has the following elements.
#Text Label and Input Box: Zip Code
#Submit button
#Use GET to search the DB
#i.e. /search?zip=98144
#Return the rows associated with that query.

#/update
#Update allows the user to update the population of a zip code:
#Serves a web page that at minimum has the following elements.
#Text Label and Input Box: Zip Code.
#Text Label and Input Box: Population.
#Submit button.
#We uses POST to update the DB using a JSON or XML- formatted message.
#Prints “Success” or “Failed” to the page depending on the result.

