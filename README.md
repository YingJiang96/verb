#verb
###A NURBS Library for the Web

verb is a JavaScript library for creating and manipulating <a href="http://en.wikipedia.org/wiki/Non-uniform_rational_B-spline">NURBS</a> surfaces and curves in the browser or <a href="http://nodejs.org/">node.js</a>.  It provides a <a href="geometry.html">rich set of geometric types like sweeps, extrusions, revolves, beziers, and other common curves and surfaces</a> in a <a href="js/verb.min.js">17kb-minified package</a>.

verb also provides advanced tools like derivative evaluation, adaptive tesselation, and intersection.  Geometry can be "watched" in a <a href="http://backbonejs.org/">backbone-like</a> style and defaults to multi-threaded parallel execution via <a href="http://en.wikipedia.org/wiki/Web_worker">WebWorkers</a> in modern browsers.  

###Latest build

The *kernel* provides nice geometric types like NurbsSurface and an abstraction around external execution of the *library*, which is the stripped down stateless library.  

+ [Latest kernel](https://raw.github.com/pboyer/verb/master/build/verb.min.js)
+ [Latest library](https://raw.github.com/pboyer/verb/master/build/verbEval.min.js)

###Getting started

Install dependencies:

	npm install

Build compiled library and documentation:

	grunt 

Run all unit tests (>140 in total):

	grunt test

###Documentation

The latest build of the documentation is located [here](http://verbnurbs.com.s3-website-us-east-1.amazonaws.com/docs/verb.html)


