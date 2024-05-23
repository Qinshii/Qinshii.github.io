<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Tags</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Game Tags Database</h1>
        <input type="text" id="searchInput" onkeyup="searchTags()" placeholder="Search for tags..">
    </header>
    <main>
        <ul id="tagsList">
            <li><a href="#tag1">Tag1</a></li>
            <li><a href="#tag2">Tag2</a></li>
            <li><a href="#tag3">Tag3</a></li>
            <!-- Add more tags as needed -->
        </ul>
    </main>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header input {
    margin-top: 10px;
    padding: 5px;
    width: 80%;
}

main {
    padding: 20px;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    background: #fff;
    margin: 5px 0;
    padding: 10px;
    border: 1px solid #ddd;
}

ul li a {
    text-decoration: none;
    color: #333;
}
