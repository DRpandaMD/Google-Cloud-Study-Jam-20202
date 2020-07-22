# Google-Cloud-Study-Jam-20202
My notes for the Google Cloud Study Jam of 2020

google code lab link : https://codelabs.developers.google.com/codelabs/sheets-api/#0

## Google Sheets as a Reporting Tool: Sheets Api

app used `git clone https://github.com/googlecodelabs/sheets-api.git`


### Command list

    1  gcloud auth list
    2  gcloud config list project
    3  git clone https://github.com/googlecodelabs/sheets-api.git
    4  ls
    5  cd sheets-api/
    6  ls
    7  cd start/
    8  ls
    9  npm install


### Lab Notes

Take a moment to familiarize yourself with the code, and refer to the table below for a general overview of the application's structure:

app.js

Configures the Express web application framework.

config.json

A configuration file, containing the database connection information.

db.sqlite

A SQLite database used to store the order records.

models/

Contains the code that defines and loads the database models. This application uses the Sequelize ORM library for reading and writing to the database.

node_modules/

Contains the project's dependencies, as installed by npm.

package.json

Defines the Node.js application and its dependencies.

public/

Contains the client side JavaScript and CSS files used by the application.

routes.js

Defines the URL endpoints the application supports and how to handle them.

server.js

The entry point into the application, which configures the environment and starts the server.

views/

Contains the HTML templates to be rendered, written using the Handlebars format. The Material Design Lite (MDL) library has been used for layout and visual appeal.

### Code snippets and sources

<https://developers.google.com/identity/sign-in/web/>

<https://developers.google.com/identity/sign-in/web/backend-auth>

https://sequelize.org/

https://github.com/googleapis/google-api-nodejs-client

https://developers.google.com/sheets/api/reference/rest/v4/spreadsheets

https://developers.google.com/sheets/api/reference/rest/v4/spreadsheets/create

https://developers.google.com/sheets/api/reference/rest/v4/spreadsheets/batchUpdate

https://developers.google.com/sheets/api/reference/rest/v4/spreadsheets/request#request