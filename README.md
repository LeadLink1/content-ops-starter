<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nom de votre commerce</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px 0;
            text-align: center;
        }

        nav {
            text-align: center;
            margin: 20px 0;
        }

        nav a {
            margin: 0 15px;
            color: #4CAF50;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
        }

        .products {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .product {
            width: 30%;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 15px;
            text-align: center;
        }

        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .contact {
            background-color: #f9f9f9;
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Nom de votre commerce</h1>
        <p>Slogan de votre commerce</p>
    </header>

    <nav>
        <a href="#">Accueil</a>
        <a href="#">Produits</a>
        <a href="#">À propos</a>
        <a href="#">Contact</a>
    </nav>

    <section>
        <h2>Nos Produits</h2>
        <div class="products">
            <div class="product">
                <img src="image1.jpg" alt="Produit 1">
                <h3>Produit 1</h3>
                <p>Description du produit 1</p>
                <p><strong>Prix: 10€</strong></p>
            </div>
            <div class="product">
                <img src="image2.jpg" alt="Produit 2">
                <h3>Produit 2</h3>
                <p>Description du produit 2</p>
                <p><strong>Prix: 15€</strong></p>
            </div>
            <div class="product">
                <img src="image3.jpg" alt="Produit 3">
                <h3>Produit 3</h3>
                <p>Description du produit 3</p>
                <p><strong>Prix: 20€</strong></p>
            </div>
        </div>
    </section>

    <section class="about">
        <h2>À propos de nous</h2>
        <p>Ici, vous pouvez raconter l'histoire de votre commerce, partager vos valeurs, et expliquer ce qui vous rend unique.</p>
    </section>

    <section class="contact">
        <h2>Contactez-nous</h2>
        <p>Adresse : 123 Rue de l'Exemple, Ville, Pays</p>
        <p>Email : contact@commerce.com</p>
        <p>Téléphone : +33 1 23 45 67 89</p>
    </section>

    <footer>
        <p>&copy; 2024 Nom de votre commerce. Tous droits réservés.</p>
    </footer>
</body>
</html>
