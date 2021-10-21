# Angular Bank

Bank APP coded in Angular CLI version 12.2.9. This application uses the GET, POST, PUT and DELETE methods while being connected to a mock JSON server

## What can the APP make?
- It' possible to create a database of clients with each one's name, address, telephone and account properties (POST method)
- You can update your clients information (PUT method)
- You can delete your clients (DELETE method)
- It's possible to see the whole list of clients (GET method)


## Watch out!
- The refresh method is yet to be implemented, so after each action you will have to reload the page in order to have access to the updated database
- The UI and UX are still under development
- Bug: the app will only retrieve the client's information on the UPDATE forms (you need to click on "Link", under the Client List component), if you start from `http://localhost:4200/` From the moment that you click on "Link", the following forms will not retrieve each client's info

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Mock Server ( database / backend )
Install the JSON-server globally using the following npm command:

`npm install -g json-server`

Start the server:

`json-server --watch db.json`

