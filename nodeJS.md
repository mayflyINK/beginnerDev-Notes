# Installing node.js
node is a runtime environement for executing javascript outside a browser to build server-side (back-end) services and applications.
- can access info outside of 'window' and 'document' objects (such as os, file system, network)
- node uses chrome v8 js engine, chrome js features are available in node.js
- asynchronous architecture (non-blocking)
- node comes with npm (node package manager) which allows you to install application/through the bash terminal

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

Config
- `npm config list` view node config settings

open bash and type
- `node --version` or `node -v` to check node version
- `npm -v` to check npm version
- `code .` launches vs code from terminal
- `npm list` view list of locally installed packages and version numbers
  - - `npm list <package name>` display package and dependencies
  - `npm list -g --depth 0` list global install node packages (`--depth 0` is top level only, no dependencies)
- `npm uninstall <package-name>` in node modules folder will uninstall local package
  - `npm uninstall -g <package-name>` If the package is installed globally, you need to add the -g / --global flag
  
Using the -S flag, or --save, this operation will also remove the reference in the package.json file.

If the package was a development dependency, listed in the devDependencies of the package.json file, you must use the -D / --save-dev flag to remove it from the file:

- `npm uninstall -S <package-name>`
- `npm uninstall -D <package-name>`
- `npm cache clean` clear npm cache (can add `--force`)
  - folder location C:\Users\user-name\AppData\Roaming\npm-cache
Installing Packages
- `npm install <package>@<version>` eg `npm install gatsby@2.17.2`

node wraps js code in a module wrapper function
- `(function (export, require, module, __filename, __dirname) {})`

#### References
Programming with Mosh - https://www.youtube.com/watch?v=TlB_eWDSMt4
