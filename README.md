<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shop</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #ff6347;
            padding: 20px;
            color: white;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        section {
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
        }
        #home {
            background-color: #ffa07a;
        }
        #products {
            background-color: #98fb98;
        }
        .product {
            display: inline-block;
            margin: 20px;
            padding: 15px;
            background-color: #fffacd;
            border-radius: 10px;
        }
        button {
            background-color: #ff4500;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
        #contact {
            background-color: #87ceeb;
        }
        footer {
            background-color: #4682b4;
            color: white;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Online Shop</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>Welcome to Our Shop</h2>
        <p>Find the best products here.</p>
    </section>
    
    <section id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>$10.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>$15.00</p>
            <button>Add to Cart</button>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@shop.com</p>
    </section>
    
    <footer>
        <p>&copy; 2025 Online Shop. All rights reserved.</p>
    </footer>
</body>
</html>
