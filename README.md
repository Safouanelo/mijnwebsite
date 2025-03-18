<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaming Headset</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: white;
        }
        header {
            background-color: #1e1e1e;
            padding: 20px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        .container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px;
        }
        .product {
            background-color: #222;
            padding: 20px;
            margin: 15px;
            border-radius: 10px;
            text-align: center;
            width: 300px;
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        .buy-btn {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #ff4500;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .buy-btn:hover {
            background-color: #e03e00;
        }
    </style>
</head>
<body>
    <header>Gaming Headsets</header>
    <div class="container">
        <div class="product">
            <img src="headset1.jpg" alt="Gaming Headset 1">
            <h2>Pro Gamer X100</h2>
            <p>High-quality surround sound en comfortabele pasvorm.</p>
            <a href="#" class="buy-btn">Koop nu</a>
        </div>
        <div class="product">
            <img src="headset2.jpg" alt="Gaming Headset 2">
            <h2>Ultra Sound Z200</h2>
            <p>Kristalhelder geluid en ruisonderdrukkende microfoon.</p>
            <a href="#" class="buy-btn">Koop nu</a>
        </div>
    </div>
</body>
</html>
