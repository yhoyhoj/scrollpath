Scroll Path
==================
A no more jQuery plugin for defining a custom path that the browser
follows when scrolling.

This is a fork of the Scrollpath plugin by Joel Besada (http://www.joelb.me) in an attempt to make it jQuery independant.
Actually it's like the original version the changes are coming.

Demo (original version): http://joelb.me/scrollpath

Fork by: Yhoyhoj 
Version: 1.1.1 (2013-05-12)

MIT Licensed (http://www.opensource.org/licenses/mit-license.php)

Introduction
---------------
Scroll Path is a plugin that lets you define your own custom scroll path. What this means exactly is best understood by [checking out the demo](http://joelb.me/scrollpath). The plugin uses canvas flavored syntax for drawing paths, using the methods moveTo, lineTo and arc. To help with getting the path right, a canvas overlay with the path can be enabled when initializing the plugin.

Scrolling can be done with the mousewheel, up/down arrow keys and spacebar. The spacebar scrolls faster than the arrow keys, and holding shift while pressing space will scroll backwards. A custom scrollbar is also included, which allows click and drag scrolling. The scrollbar is enabled by default.

The plugin also allows rotating the entire page, using CSS transforms. This can be done either along a path, or around the current position. In browsers without CSS transform support, all rotations are ignored, but paths are still followed. This means the plugin works with graceful degradation in all browsers.

As of version 1.1, the plugin also allows you to animate the scroll position to a given waypoint in the path.

Changelog
---------
__Version 1.1.1 (2012-02-20)__:
Minor bug and performance fixes. Added support for path command chaining.

__Version 1.1 (2012-02-06)__:
Added support for programmatically scrolling/animating to specified points in the path.
