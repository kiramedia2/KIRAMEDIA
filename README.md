├── index.html
├── category.html
├── article.html
├── assets/
│   ├── css/style.css
│   ├── js/script.js
│   ├── images/

<!-- index.html -->
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KiraMedia</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <header>
        <h1>KiraMedia</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="category.html">Kategori</a>
        </nav>
    </header>
    <main>
        <h2>Berita Terbaru</h2>
        <article>
            <h3><a href="article.html">Judul Berita 1</a></h3>
            <p>Deskripsi singkat berita...</p>
        </article>
    </main>
    <script src="assets/js/script.js"></script>
</body>
</html>

<!-- category.html -->
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kategori Berita - KiraMedia</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <header>
        <h1>Kategori Berita - KiraMedia</h1>
        <nav>
            <a href="index.html">Home</a>
        </nav>
    </header>
    <main>
        <h2>Berita Politik</h2>
        <article>
            <h3><a href="article.html">Judul Berita Politik</a></h3>
            <p>Deskripsi berita politik...</p>
        </article>
    </main>
</body>
</html>

<!-- article.html -->
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Detail Berita - KiraMedia</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <header>
        <h1>KiraMedia - Judul Berita</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="category.html">Kategori</a>
        </nav>
    </header>
    <main>
        <article>
            <p>Isi berita lengkap...</p>
        </article>
    </main>
</body>
</html>

/* assets/css/style.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
header {
    background: #333;
    color: white;
    padding: 10px;
    text-align: center;
}
nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

// assets/js/script.js
document.addEventListener("DOMContentLoaded", function() {
    console.log("Website KiraMedia siap!");
});
