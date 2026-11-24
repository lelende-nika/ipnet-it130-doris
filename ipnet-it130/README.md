# Mon Blog - Projet IT 130

## Description du projet

Projet réalisé dans le cadre de l'UE IT 130 - Introduction aux Technologies Web.

Il s'agit d'un site web statique en HTML5, créé sur 3 semaines de TP et publié sur GitHub Pages. Le site présente mon profil, mon blog et une page de contact complète et accessible.

Auteure : NIKA Lelende Doris
Dépôt : ipnet-it130

## Objectifs

À l'issue de ce TP, je suis capable de :
1. Créer un formulaire HTML5 complet et accessible
2. Utiliser les différents types de champs (text, email, tel, select, textarea, checkbox)
3. Associer correctement les étiquettes label aux champs de formulaire
4. Appliquer la validation native HTML5 (required, minlength, pattern)
5. Créer un tableau de données structuré et accessible
6. Intégrer un média (vidéo ou audio) dans une page Web
7. Publier mon travail sur GitHub Pages

## Structure du projet

- index.html - Semaine 1 : Page d'accueil / Présentation
- blog.html - Semaine 2 : Page Blog
- contact.html - Semaine 3 : Page de Contact complète
- README.md - Description du projet

## Contenu de la page contact.html - Semaine 3

1. Formulaire de contact
- Groupe 1 : Informations personnelles - Nom complet, Email, Téléphone (optionnel)
- Groupe 2 : Votre message - Sujet (select), Message (textarea)
- Groupe 3 : Consentement - Case RGPD (obligatoire), Newsletter (optionnel)
- Boutons : Envoyer le message / Réinitialiser
- Chaque champ a un label associé avec for et id
- Validation native : required, minlength 2 pour le nom, minlength 10 pour le message, pattern pour le téléphone
- Formulaire divisé en groupes logiques avec fieldset et legend

2. Tableaux de données
- Tableau Mes disponibilités : Jours, Matin (9h-12h), Après-midi (14h-17h), avec caption, thead, tbody, tfoot, scope col, scope row, colspan 3
- Tableau Mes compétences : Technologie, Niveau, Progression (HTML Intermédiaire 70%, CSS Débutant 30%, JavaScript Débutant 10%, Git / GitHub Débutant 40%)

3. Intégration de médias
- Vidéo de présentation avec video controls, poster, 2 sources (mp4 / webm) et texte de repli
- Fichier audio Message Audio avec audio controls, 2 sources (mp3 / ogg) et texte de repli

4. Accessibilité
- Labels associés, attributs alt sur les images, contrastes, textes de repli pour les médias, code propre, indenté et commenté.

## Technologies utilisées

- HTML5 uniquement
- Git / GitHub
- VS Code
- GitHub Pages

## Comment voir le site

1. Cloner le dépôt
2. Ouvrir index.html dans un navigateur
Ou aller directement sur GitHub Pages.

## Tests réalisés - Semaine 3

- Test 1 : champs vides -> le navigateur bloque l'envoi
- Test 2 : email invalide (abc) -> message Veuillez inclure un @
- Test 3 : message trop court -> message Veuillez allonger ce texte
- Test 4 : case RGPD non cochée -> message Veuillez cocher cette case
- Test 5 : formulaire valide -> formulaire soumis

## Auteure

NIKA Lelende Doris
2026 Mon Blog