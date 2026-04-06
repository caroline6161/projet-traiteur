# projet-traiteur
#  Projet Traiteur – Site Web Complet

Projet réalisé dans le cadre de ma formation Développeur Web Full Stack.  
Ce site propose un système complet de gestion de menus, commandes, utilisateurs et administration.

##  Fonctionnalités principales

###  Utilisateurs
- Création de compte / Connexion / Déconnexion
- Consultation des menus
- Détails d’un menu
- Ajout au panier
- Validation de commande
- Historique des commandes

###  Administration
- Tableau de bord admin
- Gestion des menus (CRUD)
- Gestion des catégories, thèmes, régimes, allergènes
- Gestion des utilisateurs
- Gestion des commandes

###  Architecture MVC
- `controllers/` : logique métier
- `models/` : accès base de données
- `views/` : pages HTML/PHP
- `public/` : CSS, JS, images
- `config/` : connexion BDD, constantes

##  Base de données
- Tables : users, menus, categories, commandes, items, allergènes, thèmes, régimes…
- Relations propres et normalisées

##  Front-end
- HTML5 / CSS3
- Design moderne et responsive
- Pages utilisateur + pages admin

##  Sécurité
- Sessions sécurisées
- Hash des mots de passe
- Vérification des rôles (admin / user)
- Protection des routes


