<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Personal Brand</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: black;
            color: white;
        }
        header {
            background-color: red;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: gray;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: gray;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>PERDIEU</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <section>
        <h2>Welcome to Your Personal Brand</h2>
        <form action="upload.php" method="post" enctype="multipart/form-data">
            <label for="audioFile">Upload Your WAV File:</label><br>
            <input type="file" id="audioFile" name="audioFile"><br>
            <input type="submit" value="Upload">
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Your Personal Brand. All rights reserved.</p>
    </footer>
</body>
</html>
