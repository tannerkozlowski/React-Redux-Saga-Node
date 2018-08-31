## Development

### Quick Start

Prerequisites:

* [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Node.js](https://nodejs.org) - 10.1.0
* [Yarn](http://yarnpkg.com/) is recommended instead of npm.

[NVM](https://github.com/creationix/nvm) might be handy for installing certain version.

Now just clone and start the app:

```sh
yarn
yarn start
```

## Deployment

```sh
nvm use 10.1.0 # use node 10.1
yarn # install dependencies
cp .env-sample .env # set up .env and change the env variable
yarn run build # make production build
yarn run start:prod # start server as prod mode from the build
```

## Legacy Boilerplate Readme

For original react-boilerplate readme, refer to `README-boilerplate.md`.