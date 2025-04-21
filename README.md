<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ModiBusLanka</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #0c0c0c;
      color: #fff;
      scroll-behavior: smooth;
    }
    header {
      background: url('https://i.imgur.com/NlXBgFI.jpg') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    header h1 {
      font-size: 4rem;
      color: #FFD700;
      text-shadow: 2px 2px #000;
    }
    header p {
      font-size: 1.5rem;
      color: #ffffff;
      margin-top: 10px;
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #FFD700;
    }
    .videos iframe {
      width: 100%;
      height: 315px;
      margin-bottom: 20px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
    }
    .contact, .social {
      text-align: center;
    }
    .social a {
      margin: 0 10px;
      color: #FFD700;
      text-decoration: none;
    }
    footer {
      background-color: #333;
      color: #FFD700;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <div>
      <h1>ModiBusLanka</h1>
      <p>Sri Lanka's No.1 Modified Bus Channel</p>
    </div>
  </header>

  <section>
    <h2>About ModiBusLanka</h2>
    <p>ModiBusLanka is all about showcasing the creativity and energy of Sri Lanka’s bus culture. From bold LED setups to insane sound systems, we highlight the finest modified buses on the island. Join us on the journey of art on wheels!</p>
  </section>

  <section class="videos">
    <h2>Latest YouTube Videos</h2>
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
  </section>

  <section>
    <h2>Bus Gallery</h2>
    <div class="gallery">
      <img src="profile.jpg" alt="Modified Bus 1">
      <img src="banner.jpg" alt="Modified Bus 2">
    </div>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:modibuslanka@gmail.com">modibuslanka@gmail.com</a></p>
  </section>

  <section class="social">
    <h2>Follow Us</h2>
    <a href="https://youtube.com/@modibuslanka">YouTube</a>
    <a href="https://facebook.com/modibuslanka">Facebook</a>
    <a href="https://tiktok.com/@modibuslanka">TikTok</a>
  </section>

  <footer>
    <p>Website created by Nitum Nimtharu</p>
  </footer>
</body>
</html>
