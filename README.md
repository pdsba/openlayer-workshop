# openlayer-workshop

Initial steps

1. First checkout project into project folder

2. Execute "npm init" command to create a package.json file in your working directory. 

3. Install the OpenLayers as dependency to your application with "npm install ol"
At this point you can ask NPM to add required development dependencies by running

4. Use parcel-bundler to add required dependencys to project using "npm install --save-dev parcel-bundler" command.

5. Add this to package.json file

{
  "name": "test",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "parcel index.html",
    "build": "parcel build --public-url . index.html"
  },
  "author": "",
  "license": "ISC"
}

Start server with "npm start"
