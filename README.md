# Wythenshawe Community Farm 2017 WordPress theme


## Compiling CSS and JavaScript files

This project uses SASS for stylesheets, and WebPack for preparing assets.

To prepare the assets, and/or continuously watch and re-compile assets use the following commands

    // To compile assets…
    $ ./node_modules/.bin/webpack
    
    // To continuously watch, and re-compile assets…
    $ ./node_modules/.bin/webpack --watch

Note that if you make changes to the WebPack config file you will need to re-start watch command.