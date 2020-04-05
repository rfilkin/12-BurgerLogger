# 13-BurgerLogger
This is an app that allows users to manage a local MySQL database of Burgers.

# Installation (for local version)
1. Clone this repository to your local machine.
2. Navigate to the repository directory and start up git bash.
3. Run the command "npm install" to install all necessary packages.
4. open the db folder
5. open the schema.sql file in your local MySQL server and run it to set up the database.
5. open the seeds.sql file in your local MySQL server and run it to add sample data to the database.

# Usage
1. Navigate to the repository directory and start up git bash.
2. Run the command "node server.js" in git bash to start up the server
3. open your browser and go to "localhost:8080" to access the app website.
4. Click inside the large text box, and type in the name of a burger to add. Press the Submit button.
5. The new burger will appear in the left column with a "Devour It!" button.
6. Click the "Devour It!" button to move a burger from the left side to the right side 

# Notes
- I ran into a "Content Security Policy" error when attempting to deploy this app on Heroku, and wasn't able to fix it.
