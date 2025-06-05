<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Douceurs Maison</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff7f0;
            color: #333;
        }
        header {
            background-color: #f8b195;
            padding: 20px;
            text-align: center;
            color: white;
        }
        nav {
            background-color: #f67280;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
        .container {
            padding: 30px;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            background-color: white;
        }
        .product img {
            width: 100%;
            max-width: 300px;
            border-radius: 10px;
        }
        footer {
            background-color: #355c7d;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
        .link-invitation {
            background-color: #fff3cd;
            border: 1px solid #ffeeba;
            padding: 15px;
            margin: 30px;
            border-radius: 8px;
            text-align: center;
        }
        .link-invitation a {
            color: #d63384;
            font-weight: bold;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Douceurs Maison</h1>
        <p>Bienvenue dans notre boutique de gâteaux faits maison !</p>
    </header>

    <nav>
        <a href="#catalogue">Catalogue</a>
        <a href="#commande">Commander</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container link-invitation">
        <p>Partagez notre site avec vos amis :</p>
        <a href="https://douceurs-maison.com">https://douceurs-maison.com</a>
    </div>

    <div class="container" id="catalogue">
        <h2>Nos Gâteaux</h2>
        <div class="product">
            <h3>Gâteau au chocolat fondant</h3>
            <img src="https://via.placeholder.com/300x200.png?text=Gateau+chocolat" alt="Gateau chocolat">
            <p>Un classique indémodable, moelleux à souhait, pour les amoureux du chocolat.</p>
            <strong>Prix : 12€</strong>
        </div>
        <div class="product">
            <h3>Tarte aux fruits frais</h3>
            <img src="https://via.placeholder.com/300x200.png?text=Tarte+fruits" alt="Tarte fruits">
            <p>Base croustillante et crème légère, garnie de fruits de saison.</p>
            <strong>Prix : 15€</strong>
        </div>
        <div class="product">
            <h3>Cheesecake à la vanille</h3>
            <img src="https://via.placeholder.com/300x200.png?text=Cheesecake" alt="Cheesecake">
            <p>Un délice onctueux avec une touche de vanille bourbon.</p>
            <strong>Prix : 14€</strong>
        </div>
    </div>

    <div class="container" id="commande">
        <h2>Commander</h2>
        <form>
            <label>Nom :<br><input type="text" name="nom" required></label><br><br>
            <label>Email :<br><input type="email" name="email" required></label><br><br>
            <label>Produit souhaité :<br>
                <select name="produit">
                    <option value="chocolat">Gâteau au chocolat</option>
                    <option value="tarte">Tarte aux fruits</option>
                    <option value="cheesecake">Cheesecake</option>
                </select>
            </label><br><br>
            <label>Quantité :<br><input type="number" name="quantite" min="1" value="1"></label><br><br>
            <button type="submit">Envoyer la commande</button>
        </form>
    </div>

    <div class="container" id="contact">
        <h2>Contactez-nous</h2>
        <p>Email : contact@douceurs-maison.com</p>
        <p>Téléphone : 06 12 34 56 78</p>
        <p>Adresse : 123 rue du Sucre, Paris</p>
    </div>

    <footer>
        <p>&copy; 2025 Douceurs Maison. Tous droits réservés.</p>
        <p>Suivez-nous : Instagram | Facebook | TikTok</p>
    </footer>
</body>
</html>
