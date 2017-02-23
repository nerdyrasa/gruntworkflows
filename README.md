# Web Workflows with Grunt.js

Developing a workflow helps with developing, testing, and deploying web applications more easily and efficiently. Tools like Grunt.js make generating workflows as easy as writing a setup file. This is an example of a Grunt-based web workflow that also uses Bower.io to quickly load frameworks such as Bootstrap, jQuery, and Mustache.js. Many argue that bower is no longer relevant, but I'm glad to have an opportunity to work through an example of its use.

## Automation Option Comparison

  * Grunt
    - The "original"
    - Configuration over code
    - Writes intermediary files between steps
    - Large plugin ecosystem
  * Gulp
    - In-memory streams (pipes)
    - Fast
    - Code over configuration
    - Large plug-in ecosystem
  * npm scripts
    - Declared in package.json
    - Leverage your OS' command line
    - Directly use npm packags
    - Call separate node scripts
    - Convention-based pre/post hooks
    - Leverage world's largest package manager
    - [Why choose npm scripts article](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8#.ythe65nf0)  
    
    
## Etcetera

  * [Bower Broke Wiredep, and how to fix it….](http://jonathanfmills.com/bower-broke-wiredep-and-how-to-fix-it/)
  * [Deploying to surge](http://surge.sh/)