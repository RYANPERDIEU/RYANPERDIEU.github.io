<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Merchandise Store</title>
    <style>
        /* Your existing CSS styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            margin-bottom: 20px;
        }
        h1 {
            margin: 0;
            font-size: 2em;
        }
        nav {
            background-color: #666;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0 15px;
            font-size: 1.2em;
        }
        section {
            padding: 20px;
            margin-bottom: 40px;
        }
        .product {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        footer p {
            margin: 0;
        }
        /* New styles for audio section */
        #audio-section {
            text-align: center;
        }
        audio {
            margin-top: 20px;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
    </style>
</head>
<body>

    <header>
        <h1>Personal Merchandise Store</h1>
        <p>Welcome to our professional merchandise store</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#shop">Shop</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>About Us</h2>
        <p>Welcome to our merchandise store! We offer a wide range of high-quality products designed to meet your needs. Browse through our collection and find something that suits your style.</p>
    </section>

    <section id="shop">
        <h2>Our Products</h2>
        <div class="product">
            <img src="your_image1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>Description of Product 1 goes here.</p>
            <p>$XX.XX</p>
        </div>

        <div class="product">
            <img src="your_image2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>Description of Product 2 goes here.</p>
            <p>$XX.XX</p>
        </div>

        <!-- Add more products as needed -->

    </section>

    <section id="audio-section">
    <h2>Listen to Our Sounds</h2>
    <audio controls>
        <source src="https://dl.dropboxusercontent.com/scl/fi/7lazisd66tpk54p1rdc4f/PERDIEU.wav?raw=1" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
</section>

    <footer>
        <p>&copy; 2024 Your Personal Merchandise Store</p>
    </footer>

</body>
</html>
