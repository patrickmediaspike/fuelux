# FuelUX [![Build Status](https://secure.travis-ci.org/ExactTarget/fuelux.png?branch=master)](http://travis-ci.org/ExactTarget/fuelux)

_Base FuelUX styles and controls_

FuelUX is under development in preparation for initial release and is not yet intended for production use.  Our aim is to help web developers integrate, manage, and customize quality frontend libraries and utilities to more efficiently develop, maintain, test, and distribute their projects.  Any improvements or fixes we make to these open source projects will be contributed upstream if they are useful to the rest of the community.

## Technologies Provided

This core FuelUX repo provides all of the styles and plugins from the revolutionary [Twitter Bootstrap](http://twitter.github.com/bootstrap) project, with the following additions:

* [AMD](http://requirejs.org/docs/whyamd.html) compatibility
* One-step install with [volo](https://github.com/volojs/volo)
* [Grunt](https://github.com/cowboy/grunt)-based build script to easily build custom distribution files
* Additional FuelUX controls, including unit tests
  * Combobox
  * Search control

We are grateful to the maintainers, contributors, and sponsors of the following technologies which make FuelUX possible:

* [jQuery](http://jquery.com) (Library for DOM, events, animation, and AJAX)

* [Twitter Bootstrap](http://twitter.github.com/bootstrap) (Modern UI components and interactions)

* [LESS](http://lesscss.org) and [recess](http://twitter.github.com/recess) (Stylesheet definition and management)

* [RequireJS](http://requirejs.org) and [volo](https://github.com/volojs/volo) (Tools for managing modular JavaScript)

* [grunt](https://github.com/cowboy/grunt) (Build tool for JavaScript projects)

## Getting Started
* Clone the repo `git clone git://github.com/ExactTarget/fuelux.git`
* Default FuelUX files for production use are located in the [dist](https://github.com/ExactTarget/fuelux/tree/master/dist) directory
* To customize, modify the JS and LESS files under [src](https://github.com/ExactTarget/fuelux/tree/master/src) then run `grunt` to regenerate your [dist](https://github.com/ExactTarget/fuelux/tree/master/dist) directory (more below)

## Documentation and Examples
_(Under development)_

## Release History
`2.0.0` _(Under development)_ First public release of FuelUX

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [grunt](https://github.com/cowboy/grunt).

### Important notes
Please don't edit files in the `dist` directory as they are generated via grunt. You'll find source code in the `src` directory!

All CSS files are regenerated on every grunt build.  Please modify styles by editing the LESS source and rerunning `grunt`.

While grunt can run the included unit tests via PhantomJS, this shouldn't be considered a substitute for the real thing. Please be sure to test the `test/*.html` unit test file(s) in _actual_ browsers.

### Installing grunt
_This assumes you have [node.js](http://nodejs.org/) and [npm](http://npmjs.org/) installed already._

1. Test that grunt is installed globally by running `grunt --version` at the command-line.
1. If grunt isn't installed globally, run `npm install -g grunt` to install the latest version. _You may need to run `sudo npm install -g grunt`._
1. From the root directory of this project, run `npm install` to install the project's dependencies.

### Installing PhantomJS

In order for the qunit task to work properly, [PhantomJS](http://www.phantomjs.org/) must be installed and in the system PATH (if you can run "phantomjs" at the command line, this task should work).

Unfortunately, PhantomJS cannot be installed automatically via npm or grunt, so you need to install it yourself. There are a number of ways to install PhantomJS.

* [PhantomJS and Mac OS X](http://ariya.ofilabs.com/2012/02/phantomjs-and-mac-os-x.html)
* [PhantomJS Installation](http://code.google.com/p/phantomjs/wiki/Installation) (PhantomJS wiki)

Note that the `phantomjs` executable needs to be in the system `PATH` for grunt to see it.

* [How to set the path and environment variables in Windows](http://www.computerhope.com/issues/ch000549.htm)
* [Where does $PATH get set in OS X 10.6 Snow Leopard?](http://superuser.com/questions/69130/where-does-path-get-set-in-os-x-10-6-snow-leopard)
* [How do I change the PATH variable in Linux](https://www.google.com/search?q=How+do+I+change+the+PATH+variable+in+Linux)

##Authors

**Adam Alexander**

+ http://twitter.com/adamalex
+ http://github.com/adamalex

**Matt Beard**

+ http://github.com/mbeard

**Bryan Kohlmeier**

+ http://github.com/bkohlmeier

**Kevin Parkerson**

+ http://github.com/kevinparkerson

**Christopher McCulloh**

+ http://github.com/cmcculloh

## Copyright and license

Copyright (c) 2012 ExactTarget

Licensed under the MIT License (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the COPYING file.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.