<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tone Foster</title>

  <style>
    body {
      background-color: black;
      margin: 0;
      min-height: 100vh;

      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .video-container {
      width: 80vw;
      max-width: 1400px;
      aspect-ratio: 16 / 9;
      margin-bottom: 1.5em;
    }

    .video-container iframe {
      width: 100%;
      height: 100%;
      border: none;
    }

    a.email {
      color: white;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 1em;
      text-decoration: none;
      opacity: 0.85;
    }

    a.email:hover {
      opacity: 0.6;
    }

    /* Mobile */
    @media (max-width: 768px) {
      .video-container {
        width: 95%;
      }
    }
  </style>
</head>

<body>

  <div class="video-container">
    <iframe
      src="https://player.vimeo.com/video/1151393208"
      allow="autoplay; fullscreen; picture-in-picture"
      allowfullscreen>
    </iframe>
  </div>

  <a class="email" href="mailto:tone@fifteentoo.com">
    tone@fifteentoo.com
  </a>

</body>
</html>
