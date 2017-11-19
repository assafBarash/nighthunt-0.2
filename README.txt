Nighthunt Developer Documentation

Pre-Requirements
	- nodejs
	- mysql server & services running

Getting Started

Common:
Contains the models and the connection to DB. from the terminal, go to the common dir and run "npm link" to make it available for the api. 
you can update connection coordinates under source\config.json

API:
There is no mock db so in order to run the API a mySQL connection must exist with "nighthunt" schema in it (create the schema if its not exist!).
 
Upon initialization, the API will sync the nighthunt schema and will initialize the relevant tables and relations.
to run the API do the following:
	- go to the API dir (nighthunt-0.2\api)
	- run "npm link @wildchild/nighthunt-common" (after 			linking the common!)
	- npm install
	- npm start

Client:
based on "start-react-app", so its preatty simple:
	- npm install
	- npm start

**Important note:
every piece of code here is "work in progress". the focus right now is on code architecture and less on fency visualizations, those will be added later.


