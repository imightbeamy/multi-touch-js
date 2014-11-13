Multitouch Javascript
==============

Presentation and demos on touch events in javascript

Demos:
* [drag and drop](https://rawgit.com/imightbeamy/multi-touch-js/master/drag_and_drop.html)
* [log events](https://rawgit.com/imightbeamy/multi-touch-js/master/log_events.html)
* [pong](https://rawgit.com/imightbeamy/multi-touch-js/master/pong.html)
* [simple](https://rawgit.com/imightbeamy/multi-touch-js/master/simple.html)
* [simple (with animation loop)](https://rawgit.com/imightbeamy/multi-touch-js/master/simple_with_animation_loop.html)
* [simple (with remove)](https://rawgit.com/imightbeamy/multi-touch-js/master/simple_with_remove.html)

# Loading these on a device

First run a server on your local machine with these files

1. Clone this repo
1. cd to the folder
1. Run... `python -mSimpleHTTPServer`

Now to hook up the device

1. Go to `chrome://inspect/#devices` (You Can also get to this through the menu under "More tools" > "Inspect Devices")
1. Click "Port forwarding..."
1. Add a line for `localhost:8000`
1. Check `Enable port forwarding`

Plug in your device and open `localhost:8000`!

You should see the index of the test files, open one and you're rolling.
