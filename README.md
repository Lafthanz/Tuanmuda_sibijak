# Tuanmuda_sibijak<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TuanMuda si Bijak dan Berani</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1 class="title">TuanMuda si Bijak dan Berani</h1>
        <div class="search-box">
            <input type="text" id="search" placeholder="Cari sesuatu...">
            <button onclick="search()">Cari</button>
        </div>
    </div>

    <script>
        function search() {
            const query = document.getElementById('search').value;
            if (query) {
                window.location.href = `https://www.google.com/search?q=${encodeURIComponent(query)}`;
            }
        }
    </script>
</body>
</html>
body {
    background-color: #f0f0f0;
    font-family: 'Arial', sans-serif;
    text-align: center;
}

.container {
    margin-top: 20%;
}

.title {
    font-size: 3em;
    color: #333;
    font-weight: bold;
    text-shadow: 2px 2px 4px #aaa;
}

.search-box {
    margin-top: 20px;
}

input[type="text"] {
    width: 300px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1em;
}

button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    background-color: #4285F4;
    color: white;
    font-size: 1em;
    cursor: pointer;
    margin-left: 10px;
}

button:hover {
    background-color: #357ae8;
}
