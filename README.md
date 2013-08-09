angular-parallax is a module for [AngularJS](http://angularjs.org/) to provide parallax-like functionality to DOM elements

Inspired by [stellar.js](http://markdalgleish.com/projects/stellar.js/)

Demos
-----

Check out the running demo [at the angular-parallax web site](http://brettdonohoo.github.com/angular-parallax).

Version Numbers
---------------

Getting Started
---------------

 * [View the source](http://brettdonohoo.github.com/angular-parallax)
 * Include the script tag on your page after the AngularJS and jQuery script tags

        <script type='text/javascript' src='path/to/angular.min.js'></script>
        <script type='text/javascript' src='path/to/angular-parallax.js'></script>

 * Ensure that your application module specifies angular-parallax` as a dependency:

        angular.module('myApplication', ['angular-parallax']);

 * Use the directive by specifying a `parallax` or `parallax-background` attribute on an element.

        <img parallax parallax-ratio="0.4" src="some/image.jpg" />
        <div parallax-background parallax-ratio="0.2"></div>

Detailed Documentation
----------------------

angular-parallax accepts several attributes to customize the behavior of the directive; detailed instructions coming soon

License
-------

angular-parallax is licensed under the MIT license. See the LICENSE file for more details.
