- inatall
  ```
  npm install -g webpack
  npm init // add a package.json configuration file
  npm info webpack
  npm install webpack[@1.2.x] --save-dev
  npm install webpack-dev-server --save-dev // use dev tools
  // watch mode: don’t want to manually recompile after every change...
  // webpack can cache unchanged modules and output files between compilations.
  webpack --progress --colors --watch
  // Webpack 开发工具
  // the development server is even better.
  // http://localhost:8080/webpack-dev-server/bundle
  npm install webpack-dev-server -g
  webpack-dev-server --progress --colors
  ```

- usage
  ```
  // webpack ./entry.js bundle.js
  // webpack ./entry.js bundle.js --module-bind 'css=style!css'
  // add a config file: webpack.config.js
  // webpack
  // If the project grows the compilation may take a bit longer. So we want to display some kind of progress bar. And we want colors…
  webpack --progress --colors
  // don’t want to manually recompile after every change…
  webpack --progress --colors --watch
  // add webpack.config.js
  webpack
  ```
