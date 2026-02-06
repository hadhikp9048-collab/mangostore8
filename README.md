<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mango Store - Online Shopping</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #ffcc00;
            padding: 10px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            padding: 14px 20px;
            text-decoration: none;
            color: white;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 20px;
            margin: 10px;
            background-color: white;
            width: 200px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        .product h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .product p {
            color: #ff6600;
            font-weight: bold;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Mango Store</h1>
        <p>Best deals on all your favorite products!</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>

    <!-- Product Listings -->
    <div class="container">
        <div class="product">
            <img src="koduvally.png" alt="Product 1">
            <h3>Product 1</h3>
            <p>₹999</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 2">
            <h3>Product 2</h3>
            <p>₹1499</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 3">
            <h3>Product 3</h3>
            <p>₹1999</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 4">
            <h3>Product 4</h3>
            <p>₹2499</p>
            <button>Add to Cart</button>
        </div>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2026 Mango Store | All Rights Reserved</p>
    </footer>

</body>
</html>
