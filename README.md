## create-react-app-docker
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Motivation
1) Create the environment needed for your build process
2) Run that build process to produce your artifact
3) Create your production environment
4) Copy the artifact into your production environment
5) Discard everything else from the build environment.
6) profit... 💵💶💴💷

## Setup

### 1) Install 3rd Party Tools
Please install all of these before doing anything.
* [docker](https://store.docker.com/editions/community/docker-ce-desktop-mac)
* [yarn](https://yarnpkg.com/en/docs/install)

### 2) Clone git repo
```shell
git clone git@github.com:mqschwanda/create-react-app-docker.git
cd create-react-app-docker
```

### 3) Add Docker Network
You only need do this once.
```shell
yarn docker-network-create
```

### 4) Start Docker
The entire app runs on Docker. To build the Docker containers:
```shell
yarn start
```

You can now visit [http://localhost:3000](http://localhost:3000) to see the application running

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn start:prod`

Runs the app in the production mode.<br />

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

[Create React App + Docker](https://medium.com/@shakyShane/lets-talk-about-docker-artifacts-27454560384f)

[Dockerizing a React App](https://mherman.org/blog/dockerizing-a-react-app/)

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

### Resources
