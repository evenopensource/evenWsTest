# EvenWsTest

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node](https://img.shields.io/badge/node-%3E%3D16-brightgreen)
![TypeScript](https://img.shields.io/badge/typescript-%3E%3D4.7-blue)

A TypeScript-based testing framework for distributed webSocket servers.
  
## Features

- Can be used to test websocket servers written in any language
- Has data scripts using which the necessary tools(redis pubsub/db/any http server) that supports the websocket server can be started
- Starts multiple websocket servers and server logs can be found in the "log" directory of the respective OS
- Simulates websocket add user, send message and remove user and checks if the websocket server behaves as intended
- Supports parallel execution of multiple test suites



## Installation and start
Install the dependencies `npm install`
Build and run `npm run build && npm run dev`



## Contributing

Feel free to submit issues and pull requests! Contributions are always welcome.

## License

This project is licensed under the MIT License.
