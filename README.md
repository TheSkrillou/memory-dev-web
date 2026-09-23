# Jeu de Memory 

Lien vers le jeu en ligne : Jouer au Memory (Lien GitHub Pages)

Description

Un jeu de Memory interactif complet développé dans le cadre du module web (BUT 2A). Le but du jeu est de retrouver les 8 paires d'images générées aléatoirement en faisant le moins de coups possible et le plus rapidement possible.

Technologies utilisées

    -HTML5 (Structure sémantique)
    -CSS3 (Mise en page via Flexbox)
    -JavaScript Vanilla (ES6) (Logique algorithmique et manipulation du DOM)
    -API externe : Lorem Picsum pour la génération des images.

Fonctionnalités clés

    -Conformément aux exigences de conception, ce projet intègre :
    -Algorithme de Fisher-Yates : Mélange performant et aléatoire du tableau de cartes.
    -Asynchronisme : Utilisation de setTimeout pour gérer le délai de mémorisation lors d'une paire incorrecte.
    -Accessibilité (A11y) : Utilisation des attributs ARIA (role="button") et de tabindex pour permettre la navigation au clavier.
    -Séparation des préoccupations : Interface DOM déconnectée de la logique algorithmique pure.

Guide de lancement local

   Pour tester ce projet sur votre machine :

    -Clonez ce dépôt localement :

        -git clone https://github.com/ton-nom-utilisateur/js-memory-game.git
        -Ouvrez le dossier dans votre éditeur de code (ex: VS Code).
        -Assurez-vous que la structure des dossiers est respectée (css/index.css et js/app.js).
        -Faites un clic droit sur le fichier index.html et choisissez Open with Live Server pour lancer le projet dans votre navigateur avec un serveur local sécurisé.
