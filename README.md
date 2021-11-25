# Create React App for sfera

<img alt="Logo" align="right" src="https://create-react-app.dev/img/logo.svg" width="20%" />

Create React apps for sfera with no build configuration.

- [Creating an App](#creating-an-app) – How to create a new app.

Create React App for sfera works on macOS, Windows, and Linux.<br>

## Quick Overview

```sh
npx create-react-app my-app --template sfera-app
cd my-app
npm install @labelgrupnetworks/02379_sertec_sfera_tools.git
npm start
```

If you've previously installed `create-react-app` globally via `npm install -g create-react-app`, we recommend you uninstall the package using `npm uninstall -g create-react-app` or `yarn global remove create-react-app` to ensure that npx always uses the latest version.

Then open [http://localhost:3000/](http://localhost:3000/) to see your app.<br>
When you’re ready to deploy to production, create a minified bundle with `npm run build`.

### Get Started Immediately

You **don’t** need to install or configure tools like webpack or Babel.<br>
They are preconfigured and hidden so that you can focus on the code.

Create a project, and you’re good to go.

## Creating an App

**You’ll need to have Node 14.0.0 or later version on your local development machine** (but it’s not required on the server).

To create a new app, you may choose one of the following methods:

### npx

```sh
npx create-react-app my-app
```
### npm

```sh
npm init react-app my-app
```

_`npm init <initializer>` is available in npm 6+_



It will create a directory called `my-app` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── eslint.js
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js
    └── src
        ├── App.css
        ├── App.js
        ├── App.test.js
        ├── index.css
        ├── index.js
        ├── logo.svg
        └── serviceWorker.js
        └── setupTests.js
        └── infrastructure
            └── assets
            └── components
            └── localization
            └── redux
            └── routes
        └── modules
            └── login
                └── hooks
                └── pages
                └── components
                                
        
    
```

No configuration or complicated folder structures, only the files you need to build your app.<br>
Once the installation is done, you can open your project folder:

```sh
cd my-app
```

Inside the newly created project
Change the content of the .npmrc file, where it says YOU'RE TOKEN for a github developer token

### `npm install @labelgrupnetworks/02379_sertec_sfera_tools.git`
### `npm start` or `yarn start`

Runs the app in development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will automatically reload if you make changes to the code.<br>
You will see the build errors and lint warnings in the console.


### `npm run build` or `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>

Your app is ready to be deployed.

## User Guide

You can find detailed instructions on using Create React App and many tips in [its documentation](https://facebook.github.io/create-react-app/).

## How to Update to New Versions?

Please refer to the lablegrup company

## Philosophy

- **One Dependency:** There is only one build dependency. It uses webpack, Babel, ESLint, and other amazing projects, but provides a cohesive curated experience on top of them.

- **No Configuration Required:** You don't need to configure anything. A reasonably good configuration of both development and production builds is handled for you so you can focus on writing code.

- **No Lock-In:** You can “eject” to a custom setup at any time. Run a single command, and all the configuration and build dependencies will be moved directly into your project, so you can pick up right where you left off.

## License

Create React App is open source software [licensed as MIT](https://github.com/facebook/create-react-app/blob/main/LICENSE). The Create React App logo is licensed under a [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/).
# sferacloud
# -02379_SERTECFARMASL_sferafarma_cloud
