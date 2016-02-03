You've probably heard of [iOS's dreaded 300ms tap delay](http://updates.html5rocks.com/2013/12/300ms-tap-delay-gone-away).  React's `onClick` attribute falls prey to it.  Facebook's working on a solution in the form of `TapEventPlugin`, but it [won't be made available](https://github.com/facebook/react/issues/436) [until 1.0](https://github.com/facebook/react/pull/1170).

If you're reading this, you're probably working on a project that can't wait until they figure out how they want to publish it.  This repo is for you.

Usage is simple:

    var injectTapEventPlugin = require("react-tap-event-plugin");
    injectTapEventPlugin();

When Facebook solves [#436](https://github.com/facebook/react/issues/436) and [#1170](https://github.com/facebook/react/pull/1170), this repo will disappear.