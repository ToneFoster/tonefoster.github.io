  <style>
    body {
      margin: 0;
      background: black;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      font-family: Arial, Helvetica, sans-serif;
    }

    .video {
      width: 70vw;
      max-width: 1100px;
      aspect-ratio: 16 / 9;
    }

    iframe {
      width: 100%;
      height: 100%;
      border: none;
    }

    .email {
      margin-top: 24px;
      font-size: 14px;
      color: white;
      text-decoration: none;
      opacity: 0.8;
    }

    .email:hover {
      opacity: 1;
    }

    @media (max-width: 768px) {
      .video {
        width: 90vw;
      }
    }
  </style>
</head>

<body>

  <div class="video">
    <iframe
      src="https://player.vimeo.com/video/1151393208?title=0&byline=0&portrait=0&badge=0"
      allow="fullscreen; picture-in-picture"
      allowfullscreen>
    </iframe>
  </div>

  <a class="email" href="mailto:tone@fifteentoo.com">
    tone@fifteentoo.com
  </a>

</body>
</html>
