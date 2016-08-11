npm init

// webpack ./entry.js bundle.js
// webpack ./entry.js bundle.js --module-bind 'css=style!css'
// add a config file: webpack.config.js
// webpack
// If the project grows the compilation may take a bit longer. So we want to display some kind of progress bar. And we want colors…
webpack --progress --colors
// don’t want to manually recompile after every change…
webpack --progress --colors --watch
