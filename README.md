# Next-up-Innovation-Ahead
To build a dynamic landing portal template that empowers brands to launch new products of any category with visual impact and clarity.

HTML CODE :

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Showcase Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>My Product Showcase</h1>
    </header>

    <!-- Product Cards Section -->
    <main class="product-container">
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 1">
            <h2>Product 1</h2>
            <p>$49.99</p>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 2">
            <h2>Product 2</h2>
            <p>$59.99</p>
        </div>
    </main>

    <script src="script.js"></script>
</body>
</html>


CSS CODE :

body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f5f5f5;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
}

.product-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 40px 0;
    flex-wrap: wrap;
}

.product-card {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    width: 200px;
    transition: transform 0.3s;
}

.product-card:hover {
    transform: scale(1.05);
}
