# Store-Miko-Lebak-io
Store news miko lebak

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Store Miko Lebak</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #0a0a0a;
      color: #fff;
    }

    header {
      background-color: #1f1f1f;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background-color: #2c2c2c;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.03);
    }

    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .card-content {
      padding: 15px;
    }

    .card-content h3 {
      margin: 0 0 10px 0;
    }

    .card-content p {
      font-size: 0.9em;
      color: #ccc;
    }

    .card-content a {
      display: inline-block;
      margin-top: 10px;
      color: #00d1ff;
      text-decoration: none;
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: #1f1f1f;
      color: #777;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Websat Miko Lebak Store</h1>
    <p>Koleksi aplikasi dan tools keren dari GitHub</p>
  </header>

  <div class="container">
    <!-- Card 1 -->
    <div class="card">
      <img src="https://via.placeholder.com/400x150" alt="App Image">
      <div class="card-content">
        <h3>Nama Aplikasi</h3>
        <p>Deskripsi singkat aplikasi atau projek.</p>
        <a href="https://github.com/username/project1" target="_blank">Lihat di GitHub</a>
      </div>
    </div>

    <!-- Card 2 -->
    <div class="card">
      <img src="https://via.placeholder.com/400x150" alt="App Image">
      <div class="card-content">
        <h3>Nama Aplikasi 2</h3>
        <p>Deskripsi aplikasi kedua yang juga keren.</p>
        <a href="https://github.com/username/project2" target="_blank">Lihat di GitHub</a>
      </div>
    </div>

    <!-- Tambahkan lebih banyak card sesuai kebutuhan -->
  </div>

  <footer>
    &copy; 2025 Toko Miko Lebak. Dibuat dengan cinta.
  </footer>

</body>
</html>
