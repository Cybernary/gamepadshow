# GAMEPADSHOW
A simple way to show off which gamepad buttons you're pressing on your stream

## How to configure and set up
This is just an HTML file with an inline SVG (also available as a standalone file) and a few lines of JS in order to show in your screen which buttons are being pressed on your gamepad.

1. Download the HTML file
1. Change the SVG if you want, just remember to keep the elements names.
1. Under **Configuration** you'll find an array that contains the buttons name, the color on press and the original button color. Change that as you wish.
1. `limit` is your joysticks movement range. Change it as you need.
1. `speed` is your joysticks movement speed. Change it as you need.
1. Once you're done with your changes, you can use the HTML file to show how you play with the gamepad on your streams. Check your streaming software on [how to add a navigation source. This example is for Streamlabs OBS](https://blog.streamlabs.com/introducing-browser-source-interaction-for-streamlabs-obs-d8fc4dcbb1fb#:~:text=How%20to%20add%20a%20Browser,the%20browser%20source%20settings%20menu.)
1. Remeber to press any button in order to activate the gamepad and enjoy!

## Known bugs
* If you use any joystick to activate the gamepad on the HTML, their movements get weird.

## Credits and sources
* https://www.w3.org/TR/gamepad/
* https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API
* https://gamepad-tester.com/
* Marcin Wichary's [Jumping the Hurdles with the Gamepad API](https://www.html5rocks.com/en/tutorials/doodles/gamepad/)

