# Installing node.js
Node is a server-side javascript environment.

#### Node for Windows (process followed for v12.18.3 LTS)
- go to https://nodejs.org and download LTS version "recommended for most users"
- lanuch install wizard and keep default settings
- select "Automatically install necessary tools"
  - if you don't select to do this automatically, you will need to install tools manually for node to work
- selecting "finish" will launch a node script to do the automatic installations using chocolatey
- press any key to continue will launch windows powershell
- downloading and installing everything will take some time.
- powershell will close when complete
- open bash and type `node` to switch node command prompts
- `console.log('hello world')` to test javascript in terminal

open bash and type
- `node -v` to check node version
- `npm -v` to check npm version
