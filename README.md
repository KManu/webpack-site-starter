# Webpack Starter For Simple Sites

This is a simple HTML, SASS, JS starter template for simple websites. It's basically copied from Joel Hernandez's [webpack-starter-basic](https://github.com/lifenautjoe/webpack-starter-basic), but with a few modifications that are more suited to my personal development tastes. Feel free to use as you wish. 

## Modifications/Tweaks
### To the production webpack config: 

* Replaced [favicon-webpack-plugin](https://github.com/jantimon/favicons-webpack-plugin) with [webapp-webpack-plugin](https://github.com/brunocodutra/webapp-webpack-plugin), which is basically an upgraded fork of the former.
* Added [uglifyjs-webpack-plugin](https://github.com/webpack-contrib/uglifyjs-webpack-plugin), configured to mangle and remove comments and console logs in production.
* Added [compression-webpack-plugin](https://github.com/webpack-contrib/compression-webpack-plugin) and configured to use [Brotli.](https://en.wikipedia.org/wiki/Brotli) 
* Added [imagemin-webpack-plugin](https://github.com/Klathmon/imagemin-webpack-plugin) to compress image assets in production.

### Other changes

* Added eslint and configured with the google style guide. 