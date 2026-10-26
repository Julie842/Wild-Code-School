# Wild-Code-School

Projet Wild Code School : formulaire d'inscription pour le WildFest 📝

📌 Présentation du projet :
Ce projet est une application web monopage (Single Page Application) développée en HTML5, CSS3 et JavaScript. L'objectif est d'offrir une interface moderne, réactive et adaptée à tous les écrans pour s'inscrire à la prochaine édition du festival.

🌟 Fonctionnalités principales :
Rendu dynamique du panier/liste : affichage et mise à jour de la liste des participants sans rechargement de la page à l'aide de templates.
Ajout de participants : prise en charge des nouvelles inscriptions via un formulaire (nom et avatar personnalisé).
Design responsive : adaptabilité complète sur mobile et écran large via des règles CSS @media et Flexbox/Grid.
Avatars dynamiques : intégration d'une API de génération d'avatars de profil.

🛠️ Technologies utilisées :
HTML5 : structuration sémantique de la page.
CSS3 moderne :
Variables CSS (:root) pour les espaces et la charte graphique.
Layout CSS Grid pour l'alignement responsive des cartes de participants.
Media queries pour une mise en page latérale sur les grands écrans.
JavaScript (ES6) : manipulation du DOM et gestion événementielle (DOMContentLoaded, preventDefault).
Mustache.js : moteur de rendu de templates côté client.
Node.js / Serve : serveur de développement statique local.

📂 Structure du projet :
├── index.html            # Structure principal HTML de la page
├── styles.css            # Styles globaux et responsive design
├── assets/
│   ├── main.js           # Logique JavaScript (Mustache.js & formulaires)
│   └── images/
│       └── wilder-land.jpg # Image de fond de l'événement
└── package.json          # Configuration du serveur local (serve)
