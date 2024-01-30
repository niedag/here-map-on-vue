# heremap-vue

## Project setup for Yarn on Windows
```
yarn install
```
For installing the Vue CLI to all users using Yarn
```
yarn global add @vue/cli
```

If @Vue/cli-service is not listed under devDependencies in package.json in the project, run
```
yarn add @vue/cli-service --dev
```

### Compiling and running the server
With Yarn 
```
yarn run serve 
```
With NVM
```
nvm run serve
```

Project source:
https://developer.here.com/tutorials/how-to-implement-a-web-map-using-vuejs/

If you are running this remotely or via a GitHub codespace, the project needs to be configured for connection over HTTPS (because it's not a local connection). 
- Install Web Socket libraries

``` yarn add socket.io-client ```
