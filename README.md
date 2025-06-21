<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MovieFlix - Watch Movies</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #111;
      color: #fff;
    }

    header {
      background-color: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      color: #e50914;
    }

    nav a {
      color: white;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }

    .search-bar {
      margin: 1.5rem auto;
      width: 80%;
      text-align: center;
    }

    .search-bar input {
      width: 60%;
      padding: 0.6rem;
      border-radius: 4px;
      border: none;
    }

    .movies-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }

    .movie-card {
      background-color: #222;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.2s;
    }

    .movie-card:hover {
      transform: scale(1.05);
    }

    .movie-card img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .movie-info {
      padding: 1rem;
    }

    .movie-info h3 {
      margin-bottom: 0.5rem;
    }

    .btn {
      background-color: #e50914;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      color: white;
      cursor: pointer;
      text-decoration: none;
    }
  </style>
</head>

<body>
  <header>
    <h1>MovieFlix</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Genres</a>
      <a href="#">Top Rated</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <div class="search-bar">
    <input type="text" placeholder="Search for a movie...">
  </div>

  <section class="movies-container">
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+1" alt="Movie 1">
      <div class="movie-info">
        <h3>Movie Title 1</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+2" alt="Movie 2">
      <div class="movie-info">
        <h3>Movie Title 2</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+3" alt="Movie 3">
      <div class="movie-info">
        <h3>Movie Title 3</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <!-- Add more movies here -->
  </section>
</body>

</html><!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MovieFlix - Watch Movies</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #111;
      color: #fff;
    }

    header {
      background-color: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      color: #e50914;
    }

    nav a {
      color: white;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }

    .search-bar {
      margin: 1.5rem auto;
      width: 80%;
      text-align: center;
    }

    .search-bar input {
      width: 60%;
      padding: 0.6rem;
      border-radius: 4px;
      border: none;
    }

    .movies-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }

    .movie-card {
      background-color: #222;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.2s;
    }

    .movie-card:hover {
      transform: scale(1.05);
    }

    .movie-card img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .movie-info {
      padding: 1rem;
    }

    .movie-info h3 {
      margin-bottom: 0.5rem;
    }

    .btn {
      background-color: #e50914;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      color: white;
      cursor: pointer;
      text-decoration: none;
    }
  </style>
</head>

<body>
  <header>
    <h1>MovieFlix</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Genres</a>
      <a href="#">Top Rated</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <div class="search-bar">
    <input type="text" placeholder="Search for a movie...">
  </div>

  <section class="movies-container">
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+1" alt="Movie 1">
      <div class="movie-info">
        <h3>Movie Title 1</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+2" alt="Movie 2">
      <div class="movie-info">
        <h3>Movie Title 2</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+3" alt="Movie 3">
      <div class="movie-info">
        <h3>Movie Title 3</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <!-- Add more movies here -->
  </section>
</body>

</html><!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MovieFlix - Watch Movies</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #111;
      color: #fff;
    }

    header {
      background-color: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      color: #e50914;
    }

    nav a {
      color: white;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }

    .search-bar {
      margin: 1.5rem auto;
      width: 80%;
      text-align: center;
    }

    .search-bar input {
      width: 60%;
      padding: 0.6rem;
      border-radius: 4px;
      border: none;
    }

    .movies-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }

    .movie-card {
      background-color: #222;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.2s;
    }

    .movie-card:hover {
      transform: scale(1.05);
    }

    .movie-card img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .movie-info {
      padding: 1rem;
    }

    .movie-info h3 {
      margin-bottom: 0.5rem;
    }

    .btn {
      background-color: #e50914;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      color: white;
      cursor: pointer;
      text-decoration: none;
    }
  </style>
</head>

<body>
  <header>
    <h1>MovieFlix</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Genres</a>
      <a href="#">Top Rated</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <div class="search-bar">
    <input type="text" placeholder="Search for a movie...">
  </div>

  <section class="movies-container">
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+1" alt="Movie 1">
      <div class="movie-info">
        <h3>Movie Title 1</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+2" alt="Movie 2">
      <div class="movie-info">
        <h3>Movie Title 2</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+3" alt="Movie 3">
      <div class="movie-info">
        <h3>Movie Title 3</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <!-- Add more movies here -->
  </section>
</body>

</html><!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MovieFlix - Watch Movies</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: #111;
      color: #fff;
    }

    header {
      background-color: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      color: #e50914;
    }

    nav a {
      color: white;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }

    .search-bar {
      margin: 1.5rem auto;
      width: 80%;
      text-align: center;
    }

    .search-bar input {
      width: 60%;
      padding: 0.6rem;
      border-radius: 4px;
      border: none;
    }

    .movies-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }

    .movie-card {
      background-color: #222;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.2s;
    }

    .movie-card:hover {
      transform: scale(1.05);
    }

    .movie-card img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .movie-info {
      padding: 1rem;
    }

    .movie-info h3 {
      margin-bottom: 0.5rem;
    }

    .btn {
      background-color: #e50914;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      color: white;
      cursor: pointer;
      text-decoration: none;
    }
  </style>
</head>

<body>
  <header>
    <h1>MovieFlix</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Genres</a>
      <a href="#">Top Rated</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <div class="search-bar">
    <input type="text" placeholder="Search for a movie...">
  </div>

  <section class="movies-container">
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+1" alt="Movie 1">
      <div class="movie-info">
        <h3>Movie Title 1</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+2" alt="Movie 2">
      <div class="movie-info">
        <h3>Movie Title 2</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <div class="movie-card">
      <img src="https://via.placeholder.com/300x400?text=Movie+3" alt="Movie 3">
      <div class="movie-info">
        <h3>Movie Title 3</h3>
        <a class="btn" href="#">Watch Now</a>
      </div>
    </div>
    <!-- Add more movies here -->
  </section>
</body>

</html>
