<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Personnelle - Développeur d'applications</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <!-- En-tête -->
    <header>
        <div class="hero">
            <h1>Jeune Développeur d'Applications & Entrepreneur</h1>
            <p>Création de solutions numériques pour innover et réussir.</p>
            <a href="#projets" class="btn">Voir mes projets</a>
        </div>
    </header>

    <!-- Section À propos de moi -->
    <section id="a-propos">
        <h2>À propos de moi</h2>
        <p>
            Bonjour ! Je suis un jeune développeur d'applications passionné, avec une approche axée sur l'innovation et l'entrepreneuriat. Mon objectif est de créer des solutions sur mesure pour améliorer l'expérience utilisateur et faciliter les processus dans divers domaines numériques.
        </p>
    </section>

    <!-- Section Projets -->
    <section id="projets">
        <h2>Mes projets</h2>
        <div class="projets-grid">
            <div class="projet">
                <h3>Projet 1 : Application mobile</h3>
                <p>Application mobile pour faciliter la gestion de tâches quotidiennes avec une interface intuitive et élégante.</p>
            </div>
            <div class="projet">
                <h3>Projet 2 : Plateforme e-commerce</h3>
                <p>Une plateforme de commerce en ligne adaptée aux petites entreprises, avec des fonctionnalités personnalisées pour les ventes en ligne.</p>
            </div>
            <!-- Ajoute plus de projets ici -->
        </div>
    </section>

    <!-- Section Contact -->
    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom" required>

            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit" class="btn">Envoyer</button>
        </form>
    </section>

    <!-- Pied de page -->
    <footer>
        <p>© 2024 Mon nom. Tous droits réservés.</p>
        <ul>
            <li><a href="#a-propos">À propos</a></li>
            <li><a href="#projets">Projets</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </footer>
</body>
</html>
