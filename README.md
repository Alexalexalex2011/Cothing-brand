<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Clothing Brand</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: linear-gradient(to bottom right, #f5f7fa, #c3cfe2);
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #000, #555);
            color: white;
            padding: 2rem;
            text-align: center;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
            margin: 0.5rem 0 0;
        }
        nav {
            background: #000;
            color: white;
            padding: 1rem 0;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 0;
        }
        nav ul li {
            margin: 0 1rem;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x600') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }
        .hero h2 {
            font-size: 2.5rem;
            margin: 0;
        }
        main {
            padding: 2rem;
        }
        .section-title {
            font-size: 2rem;
            text-align: center;
            margin-bottom: 1.5rem;
            text-transform: uppercase;
        }
        .product-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
        }
        .product {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .product:hover {
            transform: scale(1.05);
        }
        .cta-section {
            background: linear-gradient(135deg, #000, #444);
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }
        .cta-section h3 {
            margin: 0;
            font-size: 2rem;
        }
        .cta-section a {
            display: inline-block;
            margin-top: 1rem;
            padding: 0.75rem 1.5rem;
            background: white;
            color: #000;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
        }
        footer {
            background: #000;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }
        footer ul {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 0;
            margin: 0;
        }
        footer ul li {
            margin: 0 1rem;
        }
        footer ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Clothing Brand</h1>
        <p>Style that inspires.</p>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#shop">Shop</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#collections">Collections</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="hero">
        <h2>Redefine Your Style</h2>
    </div>
    <main>
        <section id="shop">
            <h2 class="section-title">Shop Our Collection</h2>
            <div class="product-gallery">
                <div class="product">
                    <h3>Product 1</h3>
                    <p>$29.99</p>
                </div>
                <div class="product">
                    <h3>Product 2</h3>
                    <p>$39.99</p>
                </div>
                <div class="product">
                    <h3>Product 3</h3>
                    <p>$49.99</p>
                </div>
                <div class="product">
                    <h3>Product 4</h3>
                    <p>$59.99</p>
                </div>
            </div>
        </section>
        <section id="about">
            <h2 class="section-title">About Us</h2>
            <p>Our clothing brand is dedicated to delivering premium style, unmatched quality, and a touch of individuality to every customer. Embrace a lifestyle that represents you.</p>
        </section>
        <section id="collections">
            <h2 class="section-title">Featured Collections</h2>
            <p>Explore exclusive seasonal collections designed with passion and care.</p>
        </section>
        <section id="cta" class="cta-section">
            <h3>Join Our Community</h3>
            <a href="#">Subscribe Now</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Clothing Brand. All Rights Reserved.</p>
        <ul>
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Terms of Service</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
    </footer>
</body>
</html>
