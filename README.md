# HTML5 Background Video

Easy CSS-only background video supported in all modern browsers and IE9+.

* Make the poster image the first frame of the video for a smooth cut when the video finishes loading
* If video is set to autoplay it should be muted by default. In this case you can simply delete the audio track when encoding the videos. This saves bandwidth as well. 
* Always use a poster image and fallback to a background image for browsers that do not support HTML5. The poster image will also be used a background on mobile devices.
* There is no Flash fallback because HTML5 is [well supported](http://caniuse.com/video). IE7/8 users will have to live with just a fallback image.

### [Full-page background demo &rarr;](http://adamwalter.github.io/html5-background-video/video-bg.html)
### [Div background demo &rarr;](http://adamwalter.github.io/html5-background-video/video-div.html)
