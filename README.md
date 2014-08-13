# grunt-base64-less

> A grunt task to base 64 encode files into less format.

## Getting Started
This plugin requires Grunt `~0.4.1`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-base64-less --save-dev
```

One the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-base64-less');
```

## The "base64Less" task

### Overview
In your project's Gruntfile, add a section named `base64Less` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  base64Less: {
    your_target: {
      // Target-specific file lists and/or options go here.
      process: [
        'wildcard/*'
      ],
      dest: "output.file",
      prefix: "font_"
    },
  },
})
```

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
0.1.0: Initial release