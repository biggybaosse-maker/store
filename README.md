<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Mon Store</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            max-width: 400px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }
        img {
            width: 100%;
            border-radius: 10px;
        }
        h1 {
            font-size: 22px;
        }
        .price {
            font-size: 20px;
            color: green;
            margin: 10px 0;
        }
        .btn {
            display: inline-block;
            background-color: #25D366;
            color: white;
            padding: 12px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
            margin-top: 15px;
        }
        .btn:hover {
            background-color: #1ebe5d;
        }
    </style>
</head>
<body>

<div class="container">
    <img src="https://via.placeholder.com/400x300" alt="Produit">
    <h1>Nom de votre produit</h1>
    <p>Petite description du produit ici.</p>
    <div class="price">29,99 €</div>

    <a class="btn" 
       href="https://wa.me/1234567890?text=Bonjour%20je%20veux%20commander%20le%20produit" 
       target="_blank">
       Commander sur WhatsApp
    </a>
</div>

</body>
</html>
