## Hi there 👋
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le Castor Aventurier</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenue dans le monde du Castor Aventurier!</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#accueil">Accueil</a></li>
            <li><a href="#galerie">Galerie</a></li>
            <li><a href="#biographie">Biographie</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="accueil">
        <h2>Découvrez notre héros castor!</h2>
        <img src="images/castor_accueil.png" alt="Castor héroïque" />
        <p>Un castor unique en son genre, équipé pour l'aventure !</p>
    </section>
    <section id="galerie">
        <h2>Galerie d'Images</h2>
        <div class="gallery">
            <img src="images/castor1.png" alt="Castor avec bazooka" />
            <img src="images/castor2.png" alt="Castor en couverture" />
            <img src="images/castor3.png" alt="Castor avec jumelles" />
            <img src="images/castor4.png" alt="Castor en camouflage" />
            <img src="images/castor5.png" alt="Castor héroïque" />
        </div>
    </section>
    <section id="biographie">
        <h2>Biographie</h2>
        <p>Notre castor est un expert des opérations secrètes, équipé d'un bazooka, d'une grenade, et d'un sens aigu de l'aventure!</p>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="name">Nom:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Le Castor Aventurier. Tous droits réservés.</p>
    </footer>
</body>
</html>



body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 1rem;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    background-color: #333;
    padding: 0;
    margin: 0;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content: center;
    padding: 1rem;
}

.gallery img {
    width: 200px;
    border: 2px solid #333;
    border-radius: 8px;
}

section {
    padding: 2rem;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}
