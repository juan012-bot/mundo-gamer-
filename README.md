# mundo-gamer-
gamers
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mundo Gamer</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #1c1c1c;
      color: #f0f0f0;
    }

    header {
      background-color: #111;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3em;
      color: #00ffcc;
    }

    nav {
      background-color: #222;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: #00ffcc;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background-image: url('https://wallpaperaccess.com/full/39617.jpg');
      background-size: cover;
      background-position: center;
      padding: 100px 20px;
      text-align: center;
      color: white;
    }

    .hero h2 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    .section {
      padding: 40px 20px;
      text-align: center;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
    }

    footer {
      background-color: #111;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mundo Gamer</h1>
  </header>

  <nav>
    <a href="#">Inicio</a>
    <a href="#">Noticias</a>
    <a href="#">Lanzamientos</a>
    <a href="#">Contacto</a>
  </nav>

  <div class="hero">
    <h2>Bienvenido al universo de los videojuegos</h2>
    <p>Descubre lo último en juegos, consolas y cultura gamer</p>
  </div>

  <div class="section">
    <h2>Juegos Destacados</h2>
    <div class="gallery">
      <img src="https://upload.wikimedia.org/wikipedia/en/5/50/Fortnite_cover.jpg" alt="Fortnite">
      <img src="https://upload.wikimedia.org/wikipedia/en/4/4e/The_Legend_of_Zelda_Tears_of_the_Kingdom.jpg" alt="Zelda">
      <img src="https://upload.wikimedia.org/wikipedia/en/9/9c/God_of_War_Ragnar%C3%B6k_cover.jpg" alt="God of War Ragnarok">
      <img src="https://upload.wikimedia.org/wikipedia/en/a/a9/Call_of_Duty_Modern_Warfare_II_cover.jpg" alt="Call of Duty">
    </div>
  </div>

  <footer>
    &copy; 2025 Mundo Gamer. Todos los derechos reservados.
  </footer>
</body>
</html>
