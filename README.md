# <!DOCTYPE html>
<html>
<head>
  <title>Loading Page</title>
  <style>
    /* Make the video fill the entire screen */
    video#video {
      position: fixed;
      right: 0;
      bottom: 0;
      min-width: 100%;
      min-height: 100%;
      width: auto;
      height: auto;
      z-index: -100;
    }
  </style>
</head>
<body>
  <video id="video" src="https://pixabay.com/videos/download/video-90877_tiny.mp4" autoplay loop></video>
  <script>
    setTimeout(function() {
      window.location.href = "https://brikhaled.github.io/brothertech.github.io/";
    }, 10000); // 10000 milliseconds = 10 seconds
  </script>
</body>
</html>
