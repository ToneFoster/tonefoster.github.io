<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TONE FOSTER</title>

  <style>
    body {
      background-color: black;
      color: white;
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      min-height: 100vh;

      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    h1 {
      font-size: 4.5em; /* BIG on desktop */
      font-weight: 700;
      margin: 0;
      letter-spacing: 0.12em;
    }

    h2 {
      font-size: 1.4em;
      font-weight: 300;
      margin: 0.6em 0 1.8em;
      text-transform: lowercase;
      opacity: 0.9;
    }

    .video-container {
      width: 80vw;          /* desktop scale */
      max-width: 1400px;    /* cinematic */
      aspect-ratio: 16 / 9;
      margin-bottom: 1.8em;
    }

    .video-container iframe {
      width: 100%;
      height: 100%;
      border: none;
    }

    a.email {
      font-size: 1em;
      color: white;
      text-decoration: none;
      opacity: 0.85;
    }

    a.email:hover {
      opacity: 0.6;
    }

    /* Mobile tuning */
    @media (max-width: 768px) {
      h1 {
        font-size: 3em;
      }

      h2 {
        font-size: 1.2em;
      }

      .video-container {
        width: 95%;
      }
    }
  </style>
</head>

<body>

  <h1>TONE FOSTER</h1>
  <h2>video editor</h2>

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
