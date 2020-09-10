# Installing node.js
node is a runtime environement for executing javascript outside a browser to build server-side (back-end) services and applications.
- asynchronous architecture (non-blocking)
- 

node comes with npm (node package manager) which allows you to install application/through the bash terminal

#### Node for Windows (process followed for v12.18.3 LTS)
- go to https://nodejs.org and download LTS version "recommended for most users"
- launch and step through install wizard, keeping default settings
- select "Automatically install necessary tools"
  - if you don't select to do this automatically, you will need to install tools manually for node to work
- selecting "finish" will launch a node script to do the automatic installations using chocolatey
- press any key to continue will launch windows powershell
- downloading and installing everything will take some time.
- powershell will close when complete
- open bash and type `node` to switch node command prompts
- `console.log('hello world')` to test javascript in terminal
- `.exit` will return to bash prompts

open bash and type
- `node -v` to check node version
- `npm -v` to check npm version

####References
Programming with Mosh - https://www.youtube.com/watch?v=TlB_eWDSMt4
