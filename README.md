<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title></title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    /* Remove any default spacing or borders */
    html, body {
      margin: 0;
      padding: 0;
      border: 0;
      background: black;
      height: 100%;
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      font-family: Arial, sans-serif;
    }

    /* Video container */
    .video {
      width: 80vw;
      max-width: 1200px;
      aspect-ratio: 16 / 9;
      position: relative;
    }

    /* Vimeo iframe */
    iframe {
      width: 100%;
      height: 100%;
      border: none;
      outline: none;
      display: block;
    }

    /* Email link under the video */
    .email {
      margin-top: 12px;
      font-size: 13px;
      z-index: 10;
    }

    .email a {
      color: #aaa;
      text-decoration: none;
    }

    .email a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="video">
    <iframe
      src="https://player.vimeo.com/video/1151393208?title=0&byline=0&portrait=0&badge=0&autopause=0"
      allow="fullscreen; picture-in-picture"
      allowfullscreen>
    </iframe>
  </div>

  <div class="email">
    <a href="mailto:tone@fifteentoo.com">tone@fifteentoo.com</a>
  </div>

</body>
</html>
