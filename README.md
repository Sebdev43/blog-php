# Blog PHP 8 - Projet d'apprentissage Dyma

Ce projet est un blog développé en PHP 8 dans le cadre de la formation Dyma. Il s'agit d'une application web permettant de créer, lire, modifier et supprimer des articles de blog avec une interface utilisateur moderne et intuitive.

## 🚀 Fonctionnalités

- **Gestion des articles**
  - Création d'articles avec titre, contenu, image et catégorie
  - Modification des articles existants
  - Suppression d'articles
  - Affichage détaillé d'un article

- **Catégorisation**
  - Filtrage des articles par catégorie
  - Affichage du nombre d'articles par catégorie

- **Interface utilisateur**
  - Design responsive
  - Navigation intuitive
  - Formulaires sécurisés avec validation

## 🛠 Technologies utilisées

- PHP 8
- HTML5
- CSS3
- JSON (pour le stockage des données)

## 📁 Structure du projet

```
blog-php/
├── data/               # Stockage des données (JSON)
├── includes/           # Fichiers d'inclusion PHP
├── public/            # Ressources publiques (CSS, images)
│   └── assets/       # Images et autres ressources
├── index.php          # Page principale
├── form-article.php   # Formulaire de création/édition
├── show-article.php   # Affichage d'un article
└── delete-article.php # Suppression d'article
```

## 🔒 Sécurité

- Validation et assainissement des entrées utilisateur
- Protection contre les injections XSS
- Filtrage des données avec `filter_input_array`

## 💻 Prérequis

- PHP 8.0 ou supérieur
- Serveur web (Apache/Nginx)
- Module PHP JSON activé

## 🚀 Installation

1. Clonez le repository
2. Configurez votre serveur web pour pointer vers le dossier du projet
3. Assurez-vous que le dossier `data` a les permissions d'écriture appropriées
4. Accédez au projet via votre navigateur

## 📝 Apprentissage

Ce projet a été réalisé dans le cadre de la formation Dyma, couvrant les concepts fondamentaux de PHP 8 :
- Programmation orientée objet
- Gestion des formulaires
- Manipulation de fichiers
- Sécurité web basique
- Structure de projet MVC simplifiée

## 📸 Aperçu du projet

![Aperçu du blog](/public/assets/image.png)

---
Développé avec ❤️ pendant ma formation sur Dyma