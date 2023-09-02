# React project overview
## Folders and files
### Node modules

These are prewritten files containing reusable JavaScript code. These files contain all of the code that makes React work. They should not be edited or changed manually.

### Public

This folder contains some image files, the manifest.json, robots.txt, and the index.html

1. manifest.json: This is a json file that gives information about how a web application should behave. Leave this file alone
2. robots.txt: This is a file for web crawlers, it is not relevant for us at this time
3. index.html: This is the markup file that React uses to render code in the browser. It is always possible to add links to this file, and you should change the title, but otherwise this file should be left alone

### src

This is the folder where your coding will be done. Index.js will mostly be left alone for now, but it is the top level of your hierarchy. Below it is App.js. Simple React applications can be coded entirely in the App.js file, but primarily you will import other components into this file.


### other files

The .gitignore file is irrelevent to your environment, you could delete it if you wanted. It contains directions for git as to what files not to keep track of, either because it is unnecessary or because the file contains sensitive information.

The package.lock file is generated when creating a React project. It keeps track of your node modules. The package.json file keeps track of important information, and contains the script commands. Always remember, to run this React project, your terminal must be in the folder that contains the package.json file
