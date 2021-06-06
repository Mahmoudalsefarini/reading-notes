# Audio, Video, Images

* HTML5 comes with elements for embedding rich media in documents — video> and audio> — which in turn come with their own APIs for controlling playback, seeking, etc. This article shows you how to do common tasks such as creating custom playback controls.

* HTML5 video and audio
The <video> and <audio> elements allow us to embed video and audio into web pages. As we showed in Video and audio content, a typical implementation looks like this:

* video controls>
  source src="rabbit320.mp4" type="video/mp4">
  source src="rabbit320.webm" type="video/webm">
  p>Your browser doesn't support HTML5 video. Here is a a href="rabbit320.mp4">link to the video/a> instead./p>
  /video>


# Exploring the CSS

* Now open the CSS file and have a look inside. The CSS for the example is not too complicated, but we'll highlight the most interesting bits here. First of all, notice the .controls styling

* Playing and pausing the video

First of all, add the following to the bottom of your code, so that the playPauseMedia() function is invoked when the play button is clicked

Now to define playPauseMedia() — add the following, again at the bottom of your code