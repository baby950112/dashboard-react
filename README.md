## React Dashboard
built with [React](https://facebook.github.io/react/), [Bootstrap](http://getbootstrap.com/), [React Router](https://reacttraining.com/react-router/) (with **Server Side Rendering**!),
[Redux](http://redux.js.org/) and [GraphQL](http://graphql.org/) based on
[React Starter Kit](https://www.reactstarterkit.com) and latest industry best practices.

[Demo](https://flatlogic.com/admin-dashboards/react-dashboard/demo). Use following credentials: user/password.

## Features
* React
* Server Side Rendering
* Mobile friendly layout (responsive)
* React Router
* Bootstrap3
* GraphQL
* Nodejs backend inegration
* Sass styles
* Webpack build
* Stylish, clean, responsive layout
* Lots of utility css classes for rapid development (flatlogic css set)
* Authentication
* CRUD operations examples
* Browsersync for the ease of development

## Quick Start

#### 1. Get the latest version

You can start by cloning the latest version of React Dashboard on your
local machine by running:

```shell
$ git clone -o react-dashboard -b master --single-branch \
      https://github.com/flatlogic/react-dashboard.git MyApp
$ cd MyApp
```

#### 2. Run `yarn install`

This will install both run-time project dependencies and developer tools listed
in [package.json](../package.json) file.

#### 3. Run `yarn start`

> [http://localhost:3000/](http://localhost:3000/) — Node.js server (`build/server.js`)<br>
> [http://localhost:3000/graphql](http://localhost:3000/graphql) — GraphQL server and IDE<br>
> [http://localhost:3001/](http://localhost:3001/) — BrowserSync proxy with HMR, React Hot Transform<br>
> [http://localhost:3002/](http://localhost:3002/) — BrowserSync control panel (UI)

Now you can open your web app in a browser, on mobile devices and start
hacking. Whenever you modify any of the source files inside the `/src` folder,
the module bundler ([Webpack](http://webpack.github.io/)) will recompile the
app on the fly and refresh all the connected browsers.

## License
