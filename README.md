# Node-js Setup for Ubuntu 22.04 

## Installation
```sh 
 sudo apt update
 curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
 sudo apt-get install -y nodejs next react react-dom
 node --version
 # my current version 18.13.0
 npm --version
 # my current version 8.19.3
```
## Running Next-js Website/App

```sh
git clone https://github.com/creativetimofficial/nextjs-material-kit.git
cd nextjs-material-kit/

npm install
npm run build
npm run start
```


