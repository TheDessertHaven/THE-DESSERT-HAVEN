<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Dessert Haven</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            text-align: center;
            background-color: #fff3e0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff7043;
            color: white;
            padding: 20px;
            font-size: 28px;
            font-weight: bold;
            letter-spacing: 1px;
        }
        .container {
            padding: 20px;
        }
        .menu-item {
            display: inline-block;
            margin: 20px;
            padding: 15px;
            border: 2px solid #ff5722;
            border-radius: 15px;
            background-color: #ffe0b2;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
        }
        button {
            background-color: #ff7043;
            color: white;
            border: none;
            padding: 10px 15px;
            margin-top: 10px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }
        button:hover {
            background-color: #e64a19;
        }
        footer {
            background-color: #ff7043;
            color: white;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>The Dessert Haven</header>
    <div class="container">
        <h2>Delicious Cakes & Pastries</h2>
        <div class="menu-item">
            <h3>Chocolate Cake</h3>
            <p>Rich and creamy chocolate delight</p>
            <p>Price: ₹500</p>
            <button onclick="window.location.href='https://www.paymentgateway.com/pay/chocolate-cake'">Order Now</button>
        </div>
        <div class="menu-item">
            <h3>Strawberry Pastry</h3>
            <p>Fresh strawberries with fluffy cream</p>
            <p>Price: ₹150</p>
            <button onclick="window.location.href='https://www.paymentgateway.com/pay/strawberry-pastry'">Order Now</button>
        </div>
    </div>
    <footer>
        Contact us: thedesserthaven@example.com | 9876543210
    </footer>
</body>
</html>
