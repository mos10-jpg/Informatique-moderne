# Création d'un fichier HTML pour le site sur l'informatique moderne
site_content = """
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informatique Moderne</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f5;
            color: #333;
        }
        header {
            background-color: #0078D7;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Informatique Moderne</h1>
        <p>Découvrez les tendances et technologies actuelles</p>
    </header>
    <nav>
        <a href="#technologies">Technologies</a>
        <a href="#cloud">Cloud Computing</a>
        <a href="#ai">Intelligence Artificielle</a>
    </nav>
    <section id="technologies">
        <h2>Technologies Modernes</h2>
        <p>L'informatique moderne englobe des domaines comme le développement web, le big data, et l'automatisation.</p>
    </section>
    <section id="cloud">
        <h2>Cloud Computing</h2>
        <p>Le cloud computing offre des solutions flexibles pour le stockage et le traitement des données.</p>
    </section>
    <section id="ai">
        <h2>Intelligence Artificielle</h2>
        <p>L'IA transforme la manière dont nous interagissons avec la technologie grâce à l'apprentissage automatique et au traitement du langage naturel.</p>
    </section>
    <footer>
        <p>&copy; 2025 Informatique Moderne. Tous droits réservés.</p>
    </footer>
</body>
</html>
"""

# Enregistrement du fichier HTML
file_path = "/mnt/data/informatique_moderne.html"
with open(file_path, "w") as file:
    file.write(site_content)

file_path
