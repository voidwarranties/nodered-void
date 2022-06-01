# nodered-void

## Installing or Upgrading Node-RED
This script will work on any Debian-based operating system, including Ubuntu, Arch and Diet-Pi. You may need to run the folllowing command first to ensure npm is able to fetch and build any binary modules it needs to install. 

```sudo apt install build-essential git curl```

Then run this script to install or upgrade node-red

```
bash <(curl -sL https://raw.githubusercontent.com/node-red/linux-installers/master/deb/update-nodejs-and-nodered)
```

open ~/.node-red/settings.js find "projects enabled" and change it to true.

## credentialSecret
While in the space ssh into voidberry (10.98.71.67) and copy the credentialSecret value from ~/.node-red/.config.projects.json

## local web interface
- Use your browser to visit http://localhost:1880 select Clone Repository and add this repository.
- If nessecary add the missing node types.
- Switch to the development branch.
