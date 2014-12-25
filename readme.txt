Bootstrap:
npm install
bower install

Building:
grunt dev -- builds the app and runs tests
grunt test -- runs just the karma tests
grunt dist -- concats & minifys the js/css files and the whole app is copied to build/ for packaging & deployment.
grunt serve -- runs a connect server using local sources
grunt serve-dist -- runs a connect server from the build/ directory