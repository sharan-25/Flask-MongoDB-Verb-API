# Flask-MongoDB-Verb-API
This project implements a Flask backend application with MongoDB integration to manage favorite verbs. It provides endpoints for retrieving verbs, adding favorites, and deleting favorites. The application is built following specific project requirements for a scripting languages course.

# Project Requirements
Implement endpoints for:
Retrieving a verb
Retrieving random verbs
Adding a favorite verb
Retrieving a favorite verb
Retrieving all favorite verbs
Deleting a favorite verb
# Technologies Used
Flask
MongoDB
Python
# Setup Instructions
Clone the repository.
Install dependencies.
Make sure MongoDB is installed and running.
Run the Flask application using python app.py.
# Endpoint Documentation
# Get a Verb
URL: /verbs/
Method: GET
Description: Retrieves a specific verb.
# Get Random Verbs
URL: /verbs/random/
Method: GET
Description: Retrieves random verbs.
# Add a Favorite
URL: /verbs/favorites/
Method: POST
Description: Adds a verb to favorites.
# Get One Favorite
URL: /verbs/favorites/<favoriteUid>/
Method: GET
Description: Retrieves a specific favorite verb.
# Get All Favorites
URL: /verbs/favorites/
Method: GET
Description: Retrieves all favorite verbs.
# Delete a Favorite
URL: /verbs/favorites/<favoriteUid>/
Method: DELETE
Description: Deletes a favorite verb.
# Authors
Harsharan kaur
