<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MayaChannel</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron&family=Roboto+Mono&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #121212; /* Escuro para um visual nerd moderno */
      color: #e0e0e0; /* Cor clara para contraste */
      font-family: 'Roboto Mono', monospace;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    header {
      background-color: #333; /* Escuro com um toque de cinza */
      text-align: center;
      padding: 30px 20px;
      border-bottom: 5px solid #00ffcc; /* Neon verde para dar destaque */
    }

    header h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 48px;
      color: #00ffcc; /* Neon verde */
      margin: 0;
    }

    main {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 40px;
      gap: 20px;
    }

    .movie {
      text-align: center;
      background-color: #1e1e1e; /* Fundo escuro para as divs de filmes */
      border-radius: 10px;
      padding: 15px;
      width: 280px;
      box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.5);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .movie:hover {
      transform: translateY(-10px); /* Efeito hover para dar um "salto" */
      box-shadow: 0px 20px 30px rgba(0, 255, 204, 0.4); /* Brilho de neon */
    }

    .movie img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.7);
    }

    .movie h2 {
      font-family: 'Orbitron', sans-serif;
      color: #00ffcc;
      margin: 15px 0;
      font-size: 22px;
      text-transform: uppercase;
    }

    .movie a {
      display: inline-block;
      margin-top: 10px;
      text-decoration: none;
      color: #121212;
      font-weight: bold;
      background-color: #00ffcc;
      padding: 10px 20px;
      border-radius: 5px;
      box-shadow: 0px 5px 10px rgba(0, 255, 204, 0.3);
      transition: background-color 0.3s ease, box-shadow 0.3s ease;
    }

    .movie a:hover {
      background-color: #00b3a6; /* Neon mais escuro ao passar o mouse */
      box-shadow: 0px 10px 15px rgba(0, 255, 204, 0.5);
    }

    footer {
      background-color: #333;
      text-align: center;
      padding: 20px;
      color: #e0e0e0;
      font-size: 14px;
      border-top: 5px solid #00ffcc;
    }

    .category {
      text-align: center;
      width: 100%;
      margin-top: 40px;
    }

    .category h2 {
      font-family: 'Orbitron', sans-serif;
      color: #00ffcc;
      font-size: 36px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>MayaChannel</h1>
  </header>

  <main>
    <div class="movie">
      <h2>Moon</h2>
      <img src="https://m.media-amazon.com/images/I/81O6H2Nrg-L._AC_SY679_.jpg" alt="Moon Poster">
      <br>
      <a href="https://www.youtube.com/watch?v=40pFHR33O_k" target="_blank">Assistir Moon</a>
    </div>
    <div class="movie">
      <h2>Coherence</h2>
      <img src="https://m.media-amazon.com/images/I/81XqV3O-y+L._AC_SY679_.jpg" alt="Coherence Poster">
      <br>
      <a href="https://www.youtube.com/watch?v=GoJ7rQqgRRA" target="_blank">Assistir Coherence</a>
    </div>
    <div class="movie">
      <h2>Primer</h2>
      <img src="https://m.media-amazon.com/images/I/71vW8cB1cIL._AC_SY679_.jpg" alt="Primer Poster">
      <br>
      <a href="https://www.youtube.com/watch?v=9cGoRIpknHY" target="_blank">Assistir Primer</a>
    </div>
  </main>

  <main class="category">
    <h2>Lançamentos</h2>
  </main>

  <main>
    <div class="movie">
      <h2>The Vast of Night</h2>
      <img src="https://m.media-amazon.com/images/I/71TRaCmwH7L._AC_SY679_.jpg" alt="The Vast of Night Poster">
      <a href="https://www.youtube.com/watch?v=U2B0mc-yl54" target="_blank">Mais Informações</a>
    </div>
    <div class="movie">
      <h2>Timecrimes</h2>
      <img src="https://m.media-amazon.com/images/I/61AqaV6wqkL._AC_SY679_.jpg" alt="Timecrimes Poster">
      <a href="https://www.youtube.com/watch?v=KzJX79CmI2c" target="_blank">Mais Informações</a>
    </div>
    <div class="movie">
      <h2>Dark City</h2>
      <img src="https://m.media-amazon.com/images/I/91x0yFbS0gL._AC_SY679_.jpg" alt="Dark City Poster">
      <a href="https://www.youtube.com/watch?v=3sIHnoiw2vQ" target="_blank">Mais Informações</a>
    </div>
  </main>

  <footer>
    <p>&copy; 2024 MayaChannel - Todos os direitos reservados.</p>
  </footer>

</body>
</html>

