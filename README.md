//html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Anime OTT</title>
</head>
<body>
    <header>
        <h1>Anime OTT</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Anime List</a></li>
                <li><a href="#">Genres</a></li>
                <li><a href="#">My Watchlist</a></li>
            </ul>
        </nav>
    </header>

    <section id="featured">
        <!-- Featured anime section -->
        <h2>Featured Anime</h2>
        <!-- Display featured anime thumbnails or information -->
    </section>

    <section id="anime-list">
        <!-- Anime list section -->
        <h2>Anime List</h2>
        <!-- Display a list of available anime -->
    </section>

    <footer>
        <p>&copy; 2023 Anime OTT. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>




//css

body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

section {
    margin: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em;
    position: fixed;
    bottom: 0;
    width: 100%;
}

