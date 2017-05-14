# Item_catalog
This is a python module that creates a website and JSON API for a list of items grouped into a category. Users can edit or delete items they've creating. Adding items, deleteing items and editing items requiring logging in with Google Id.

# Instructions to run:

# Set Up Google Id:
1. go to https://console.developers.google.com/project and login with Google.
2. Create a new project
3. Name the project
4. Select "API's and Auth-> Credentials-> Create a new OAuth client ID" from the project menu
5. Select Web Application
6. On the consent screen, type in a product name and save.
7. In Authorized javascript origins add: http://0.0.0.0:8080 http://localhost:8080
8. Click create client ID
9. Click download JSON and save it into the root director of this project.
10. Rename the JSON file "client_secret.json"

# Steps to run

1. Enter into the project folder in command line.
2. Type python database_setup.py to initialize the database.
3. Type python lotsofmenus.py to populate the database.
4. Type python project.py to run the Flask web server.
5. Visit http://localhost:5000 to run.
