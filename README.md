# Webpack Skeleton

## Initialization

It's common webpack project.

> yarn install

## Usage

For building your bundle You must run:

> yarn run build

Or start development server:

> yarn start

### Scripts

It's configuration uses environment separation. For settings special environment
you must set `NODE_ENV`. The default environment is `development`.

**Package scripts:**

| Command        | Description                                     |
| -------------- | ----------------------------------------------- |
| start          | Start the development server.                   |
| build          | Build your bundles with unassigned environment. |
| watch          | Watch changes with unassigned environment.      |
| eslint         | Check your project with eslint.                 |
| eslint:fix     | Fix project conflicts with eslint.              |
| precommit      | Run precommit hook                              |
| prettier       | Handle application files with Prettier.         |
| prettier:write | Write handling of Prettier in your source.      |

## Project structure

| Path              | Description                            |
| ----------------- | -------------------------------------- |
| /app              | Your application                       |
| /app/assets       | Assets (such as fonts, images, etc)    |
| /app/app.js       | Application entry point                |
| /app/index.html   | Application startup html               |
| /config           | Project configuration                  |
| /config/misc      | Other configuration scripts            |
| /config/variables | Webpack variables for your application |
| /config/webpack   | Webpack configuration by environments  |
| /dist             | Webpack bundle                         |
| /vendor           | Vendor libs                            |
