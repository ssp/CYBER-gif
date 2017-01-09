# ![CYBER](https://github.com/ssp/CYBER-gif/blob/master/CYBER.gif)

For your proper CYBER-experience you need an animated GIF.

This one is based on the CC-BY-NC graphic created for [Cyberband](https://cyber.equipment), shrunk and scrolling through a 32x32 square with the background set to [PANTONE CYBER Yellow](https://www.pantone.com/color-finder/14-0760-TPX).

Useful, say, to use as a Slack Emoji!


## Creation

* CYBER-pdf imported to [Sketch](http://www.sketchapp.com)
* shrunk to the needed size
* tediously equipped with 32x32 masks for each frame
* exported as single image PNGs
* converted to GIF using the (Mac OSX) [sips](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man1/sips.1.html) command `find Frames -name "*png" -print0 | xargs -0 -I % sips -s format gif % --out "Frames/%.gif"`
* turned into an animated GIF using [gifsicle](https://github.com/kohler/gifsicle) `gifsicle --optimize --loopcount Frames/*gif > CYBER.gif`