.jshintrc
=========

JS Hint configuration file, for editors, grunt-contrib-jshint, etc

This configuration file is roughly based on our [javascript styleguide](https://github.com/Rhinofly/idiomatic.js).

Note: define & require are set as globals, since most of our projects use requirejs. Disable or add more globals as required.

## How to use with [grunt-contrib-jshint](https://github.com/gruntjs/grunt-contrib-jshint)?
```
    jshint: {
      options: {
        jshintrc: true,
      }
    }
```

Add the .jshintrc file in the same directory (or higher) as Gruntfile.js / Gruntfile.coffee.

## How to use with sublimelinter?

Put the .jshintrc file in the working directory (or higher)

>JSHint will look for this file in the current working directory and, if not found,
will move one level up the directory tree all the way up to the filesystem root.

## Updates to this file

Not happy with a setting? Let's make it better.
Please make a pull request with a comment why a setting should be changed.