# Cezerin is React and Node.js based eCommerce platform. React Shopping Cart.

Cezerin - Ecommerce Progressive Web Apps. Complete Solution.

## Cezerin Platform:

1. Cezerin API - Backend.
2. Cezerin Store - Frontend.
3. Cezerin Admin - Dashboard.
4. Cezerin Client - JavaScript client for Cezerin REST API.

## Built with:

- NodeJS
- ReactJs
- Redux
- ExpressJs
- Babel
- WebPack
- MongoDB

### Requirements

- [Node.js - LTS](https://nodejs.org/en)
- [Yarn](https://yarnpkg.com/getting-started/install)
- [MongoDB](https://docs.mongodb.com/manual/installation)


## Application Structure

```
.
├── config                   # Project and build configurations
├── dist                     # Distribution folder
├── locales                  # Text files
├── logs                     # Log files
├── public                   # Static public assets and uploads
│   ├── admin                # Dashboard index.html
│   ├── admin-assets         # Dashboard assets
│   └── content              # Store root folder
|
├── scripts                  # Shell scripts for theme install/export
├── src                      # Application source code
│   ├── admin                # Dashboard application
│   │   └── client           # Client side code
│   ├── api                  # REST API
│   │   └── server           # Server side code
│   ├── store                # Store application
│   |   ├── client             # Client side code
│   |   ├── server             # Server side code
│   |   └── shared             # Universal code
│   └── index.js             # Server application start point
├── theme                    # Theme as a local package
└── process.json             # pm2 process file
```

## NPM Scripts

| `npm run <script>`    | Description                                                               |
| --------------------- | ------------------------------------------------------------------------- |
| `setup`               | Run Cezerin mongodb setup.                                                |
| `compile`             | Compiles the store to disk (`~/dist` by default).                         |
| `compile:watch`       | Compiles the store and theme to disk **and watch** (`~/dist` by default). |
| `webpack:admin`       | Assemble admin bundles.                                                   |
| `webpack:store`       | Assemble store bundles.                                                   |
| `webpack:admin:watch` | Assemble admin bundles **and watch**.                                     |
| `webpack:store:watch` | Assemble store bundles **and watch**.                                     |
| `theme:install`       | Install theme from /public/<file>.zip                                     |
| `theme:export`        | Zip current theme to /public/<file>.zip                                   |
| `theme:compile`       | Compile theme after modification.                                         |
| `theme:build`         | Refresh theme after modification.                                         |
| `build`               | Compile and assemble bundles.                                             |
| `build:watch`         | Compile and assemble bundles **and watch**.                               |
| `lint`                | Check project with eslint.                                                |
| `lint:fix`            | Check and fix project with eslint.                                        |
| `format`              | Format project with prettier.                                             |
| `start:api`           | Start node server.                                                        |
| `start:store`         | Start store server.                                                       |
| `start`               | Start Cezerin.                                                            |
| `watch:api`           | Start node server **and watch**.                                          |
