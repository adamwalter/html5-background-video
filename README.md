# HTML5 Video Background

Easy CSS-only background videos.

* **Browser support:** Modern browsers, IE9+
* For IE8 support, use [HTML5 Shiv](https://code.google.com/p/html5shiv/) and `video { display: block; }`
* Make the poster image the first frame of the video for a smooth cut when the video finishes loading
* If video is set to autoplay it should be muted by default. In this case you can simply delete the audio track when encoding the videos. This saves bandwidth as well. 
* Always use a poster image and fallback to a background image for browsers that do not support HTML5. The poster image will also be used a background on mobile devices.

### [Full-page background demo &rarr;](http://adamwalter.github.io/html5-video-background/video-bg.html)
### [Div background demo &rarr;](http://adamwalter.github.io/html5-video-background/video-div.html)
