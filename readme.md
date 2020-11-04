# Aurelia 2 app to be hosted as an Azure Static Web app

This is a smalll demo of setting up an Aurelia 2 app on the Azure Static Web Apps service.
The code demo was made for a talk for the East Sweden Microsoft User Group in 2020-11-03.

## Running the Code Locally

### Prerequisites

Some tooling needs to be installed:

- Node/npm
- VS Code Static Web App plugin
- Azure Functions Tooling

### The Aurelia 2 App

To start the web project, run:

- npm install
- npm start

### The Azure Functions API

To start the API project from VS Code just press F5.

## Deploying to an Azure Web App

1. Create a new Static Web App from VS Code with the VS Code tooling.

- Connect the app to the repository

2. Change a file and push to master to trigger the CI/CD workflow that will build and deploy the app.

## More Information

More Aurelia 2 related information and helpful blogposts can be found at https://mobilemancer.com
