# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


# BLOG-web-app


node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module '../routes/auth'
Require stack:
- C:\Users\SRISHTI\reactblog\api\index.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15) 
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (C:\Users\SRISHTI\reactblog\api\index.js:6:19)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1155:10)   
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ 'C:\\Users\\SRISHTI\\reactblog\\api\\index.js' ]
}
[nodemon] app crashed - waiting for file changes before starting...
  
  
  ussualy occurs when we do not put the correct name of any folder, or incorrect path
  
  Error: connect ECONNREFUSED 127.0.0.1🈵
  
  occurs when there is a mistake with the URL we are using.
  
  node:internal/errors:464
    ErrorCaptureStackTrace(err);
    ^

> Error [ERR_HTTP_HEADERS_SENT]: Cannot set headers after they are sent to the client
    > at new NodeError (node:internal/errors:371:5)
    > at ServerResponse.setHeader (node:_http_outgoing:576:11)
    > at ServerResponse.header (C:\Users\SRISHTI\reactblog\api\node_modules\express\lib\response.js:794:10)
    > at ServerResponse.send (C:\Users\SRISHTI\reactblog\api\node_modules\express\lib\response.js:174:12)
    > at ServerResponse.json (C:\Users\SRISHTI\reactblog\api\node_modules\express\lib\response.js:278:15)
    > at C:\Users\SRISHTI\reactblog\api\routes\auth.js:35:28 {
  > code: 'ERR_HTTP_HEADERS_SENT'
}
[nodemon] app crashed - waiting for file changes before starting...
  
  occurs when your code sends multiple headers, and hence using return before all res will solve the issue.
