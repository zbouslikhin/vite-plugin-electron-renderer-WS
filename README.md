- vite-plugin-electron-renderer doesn't seem to be playing well with the [WS](https://github.com/websockets/ws) library 

# WS is undefined after build
- Run `yarn package`
- Start the packaged application and check the console

# Error after importing WS
- In console, there should be such an error
![alt text](./bug.png)