<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Official site of DJ SEMPI WOLF — musician, DJ, and owner of Pose Club.">
  <meta property="og:title" content="DJ SEMPI WOLF — Music, Technology, and Inspiration">
  <meta property="og:description" content="Discover the world of DJ SEMPI WOLF — electronic music innovator and Pose Club owner. Explore his cultural contributions and NFT gallery.">
  <meta property="og:image" content="path_to_preview_image.jpg">
  <meta property="og:url" content="https://yourwebsite.com">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="DJ SEMPI WOLF">
  <meta name="twitter:description" content="Electronic music, innovation, and art by DJ SEMPI WOLF.">
  <meta name="twitter:image" content="path_to_preview_image.jpg">
  <title>DJ SEMPI WOLF</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
  <style>
    /* Base Styles */
    :root {
      --primary-color: #ff00ff;
      --background-color: #0d0d0d;
      --header-color: #1a1a1a;
      --text-color: #fff;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      background-color: var(--background-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    a {
      color: var(--text-color);
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: var(--primary-color);
    }

    /* Header */
    header {
      text-align: center;
      padding: 30px 15px;
      background-color: var(--header-color);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 2.5rem;
      margin: 0;
    }

    .cyber-text {
      font-size: 1.2rem;
      color: var(--primary-color);
      opacity: 0;
      transition: opacity 1.5s ease-in-out;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px 0 0;
    }

    nav ul li a {
      padding: 8px 15px;
      border-radius: 5px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    nav ul li a:hover {
      background-color: var(--primary-color);
    }

    /* Sections */
    section {
      padding: 60px 20px;
      text-align: center;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .content {
      max-width: 800px;
      margin: 0 auto;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 15px;
      justify-items: center;
    }

    .gallery img {
      width: 100%;
      max-width: 300px;
      height: auto;
      border-radius: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 5px 15px rgba(255, 0, 255, 0.5);
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background-color: var(--header-color);
      font-size: 0.9rem;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        gap: 10px;
      }

      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>DJ SEMPI WOLF</h1>
    <p class="cyber-text">Technology, Music, and Inspiration</p>
    <nav>
      <ul>
        <li><a href="#about">About DJ</a></li>
        <li><a href="#contribution">Contribution</a></li>
        <li><a href="#gallery">NFT Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main Content -->
  <main>
    <!-- About Section -->
    <section id="about">
      <h2>About DJ SEMPI WOLF</h2>
      <div class="content">
        <p>DJ SEMPI WOLF and his partner KRYST have made a significant contribution to the development of electronic culture in Ukraine...</p>
        <p>Large-scale events have become symbols of freedom and unity, featuring advanced technology...</p>
      </div>
    </section>

    <!-- Contribution Section -->
    <section id="contribution">
      <h2>Contribution to Cultural Development</h2>
      <div class="content">
        <ul>
          <li>Organizing events with leading European artists.</li>
          <li>Creating cybernetic shows using robotic technologies.</li>
          <li>Attracting an international audience through innovation and creativity.</li>
        </ul>
      </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
      <h2>NFT Gallery</h2>
      <div class="gallery">
        <img src="nft1.webp" alt="Abstract digital NFT artwork by SEMPI WOLF" loading="lazy">
        <img src="nft2.webp" alt="Futuristic NFT by SEMPI WOLF" loading="lazy">
        <img src="nft3.webp" alt="Digital art NFT by SEMPI WOLF" loading="lazy">
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact</h2>
      <div class="content">
        <ul>
          <li>Email: <a href="mailto:sempiwolf@mail.com">sempiwolf@mail.com</a></li>
          <li>Instagram: <a href="https://instagram.com/sempiwolf">@sempiwolf</a></li>
          <li>Pose Club: <a href="https://poseclub.com">poseclub.com</a></li>
        </ul>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 DJ SEMPI WOLF & KRYST. All rights reserved.</p>
  </footer>

  <script>
    document.addEventListener("DOMContentLoaded", () => {
      const cyberText = document.querySelector(".cyber-text");
      setTimeout(() => {
        cyberText.style.opacity = 1;
      }, 500);
    });
  </script>
</body>
</html>
