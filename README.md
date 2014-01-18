# GT Snowracer
## Yeoman Webapp, without the Yeoman

Sorry Yeoman. No offense. But you were doing all the work and I had no idea how. Thanks to your repo though, I figured it out, and in the process I learned a hell of a lot about grunt.

So in the interest of doing this backwards, GT Snowracer is here to get everything going that Yeoman Webapp Generator can, so that people like me can learn how it all works before sticking the training wheels back on.

Naturally, the Yeoman magic of automatically building your Gruntfile based on your preferences is gone. But that's ok for now. Dig in to their repo if you'd like to learn how.

## Installation

Clone this repo into any folder. Type npm install && bower install in that folder's terminal. Then type grunt. 

## Building your dist folder

All your work should be done within the app folder. Anything ready for production should come from your dist folder, where your css and js will be concatenated and uglified. 

From the terminal: grunt build.

## Running livereload server

From the terminal: grunt server.

## Running server on dist folder

From the terminal: grunt server:dist

## Regrets

Should have called this Toboozening.