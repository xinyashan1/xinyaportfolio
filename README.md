# xinyaportfolio
My portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Xinya Shan</title>
  <style>
    body {
      background-color: #fdf5f0; /* Light Beige */
      font-family: 'Georgia', serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      padding: 20px;
    }
    .photobooth-layout {
      position: relative;
      display: flex;
      align-items: center;
      justify-content: flex-start;
      max-width: 1000px;
      margin: auto;
    }
    /* Foregrounded Polaroid / Photo Strip */
    .photo-strip {
      position: relative;
      z-index: 2;
      transform: translateX(-50px) rotate(-5deg);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    }
    .photo-strip img {
      width: 300px;
      border-radius: 10px;
    }
    /* Bio Card pushed to the right, behind photo */
    .info-card {
      background-color: #fff;
      padding: 30px;
      border-radius: 12px;
      border: 5px solid #f4c2c2; /* Soft Pink Border */
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
      max-width: 400px;
      color: #5d4157;
      line-height: 1.6;
      text-align: left;
      position: relative;
      z-index: 1;
      margin-left: -30px;
    }
    .info-card h2 {
      margin-top: 0;
    }
    .info-card a {
      color: #b0806b;
      text-decoration: underline;
    }
    .info-card a:hover {
      color: #a05252;
    }
  </style>
</head>
<body>

  <section class="photobooth-layout">
    <!-- Film Strip / Polaroid in Front -->
    <div class="photo-strip">
      <img src="Images/vintage-photostrip.png" alt="Polaroid Photo Strip">
    </div>

    <!-- Bio / Info Card -->
    <div class="info-card">
      <h2>Xinya Shan’s Photobooth</h2>
      <p>Hi, I’m Xinya Shan—an explorer at heart who loves puppies, airport adventures, and creating digital experiences. With a background in front-end web development, UX design, and cloud computing, I build clean and user-friendly websites using HTML, CSS, JavaScript, and GitHub.</p>
      <p>Follow along for sneak peeks and fun creative experiments!</p>
      <p>
        <a href="https://github.com/xinyashan1" target="_blank">GitHub</a> |
        <a href="https://www.linkedin.com/in/xinyashan/" target="_blank">LinkedIn</a>
      </p>
    </div>
  </section>

</body>
</html>


