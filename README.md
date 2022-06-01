# nodered-void

## Installation on Ubuntu
```
sudo apt install git npm
sudo npm install -g --unsafe-perm node-red
```
open ~/.node-red/settings.js and change "projects enabled" to true.


While in the space ssh into voidberry (10.98.71.67) and copy the credentialSecret value from ~/.node-red/.config.projects.json


Use your browser to visit http://localhost:1880 select Clone Repository and add this repository.

If nessecary add the missing node types. (dependencies)

In your node-red, witch to the development branch.
