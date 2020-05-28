### Pre-requirements

- [Node.js](https://nodejs.org/en/download/) v12.14.1
- npm v6.13.4 (has been integrated into Node.js)

### Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

### Deploy

After the build, The `dist` folder will be generated under the project folder, and there is a file named index.html and a folder named static under `dist`. Then:

1. Put the `index.html` into the `app/template` folder of the webserver (Flask), as the home page returned by the server (also the only page).
2. Put the `static` folder and all its contents into the `app` folder of the webserver.