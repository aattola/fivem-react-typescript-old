# FiveM React Typescript Eslint Boilerplate

Boilerplate for [FiveM](https://fivem.net/) with [React](https://reactjs.org/) [Typescript](https://www.typescriptlang.org/) [Eslint](https://eslint.org/) using [Classic Yarn](https://classic.yarnpkg.com/lang/en/) workspaces.

Includes Eslint for client server and ui with typechecking.


## Requirements
* Brains
* [Yarn](https://classic.yarnpkg.com/lang/en/)
* Basic understanding of web development with react and some understanding of fivem resources.
* Basic idea of [yarn workspaces](https://classic.yarnpkg.com/en/docs/workspaces/)

## How to use
1. Download this repo and extract
2. Rename folder to something great and innovative
3. Place folder to your Cfx server resources folder
4. Add `ensure your_resource_name_here` to your server.cfg
5. `yarn install` in root of the project
6. Start making content using commands listed below

## Development

``yarn watch:ui`` Launches web browser with UI. You can also develop in game with this mode.

``yarn watch:client`` Starts watching for changes in client and rebuilds on change. Works also in game.

``yarn watch:server`` Starts watching for changes in server and rebuilds on change. Works also in game.

## Building

``yarn build``

**NOTE:** This command will give out error code 1. Even if the build was success. If the last lines read: "File sizes after gzip:" then the build was success.


## Acknowledgements

React utils are from Project Error. You can read more about the utils at [Project Error react boilerplate](https://github.com/project-error/fivem-react-boilerplate-lua)
