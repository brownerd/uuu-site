# ugh


  "scripts": {
    "start": "webpack-dev-server --config=config/webpack.dev.js",
    "build": "BABEL_ENV=production webpack --config=config/webpack.prod.js --env.NODE_ENV=production ",
    "build:dev": "webpack --config=config/webpack.dev.js",
    "dev": "nodemon --inspect --watch src/server --watch config src/server/main.js",
    "prod": "NODE_ENV=production node --inspect src/server/main.js"



#

// HMR
npm install --save-dev webpack-hot-middleware webpack-dev-middleware