# js-dev-env
 Javascript Development Environment

	Installations & Terminal Commands:
	- for editorconfig 
		- (cmd + p)
		- enter (ext install EditorConfig) and install the top result
	- Node & npm 
		- Download nodeJs LTS version, (npm install) 
	- Express 
		- Use (node buildScripts/srcServer.js) to run the server
	- Sharing Work in Progress 
		- (npm install localtunnel) 
		- run server with express
		- type in a new terminal (lt --port 3000 --subdomain liamMorgan)
	- Authomation 
		- the script in package.json allows easier server running by changing the run 
			command from the one used with express to (npm start)
		- these can be used to run easier commands for local tunnel 
			"localtunnel": "lt --port 3000", "share": "npm-run-all --parallel start localtunnel" 
			with these the command to run everything is (npm run share)
	- EsLint
		- to run signle use lint use (npm run lint)
		- to run continuous linting use (npm run lint:watch)
		- Added now to (npm start) no need for the above two unless just running a lint test
	- Testing
		- run (npm test or npm t) to run the tests
