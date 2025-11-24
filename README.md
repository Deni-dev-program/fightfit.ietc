# FightFit Store 🥊

Site vitrine moderne et responsive pour un magasin de vêtements et équipements de sports de combat (MMA, Boxe, Muay Thai, Jiu-Jitsu Brésilien).

## 📋 Description

FightFit Store est un site web statique développé en HTML5 et CSS3, offrant une expérience utilisateur optimale sur tous les appareils. Le site présente une boutique en ligne dédiée aux passionnés de sports de combat, avec une interface moderne et intuitive.

## 🚀 Fonctionnalités

- **5 pages principales** : Accueil, Produits, Disciplines, À propos, Contact
- **Design responsive** : Adaptation automatique pour mobile, tablette et desktop
- **Navigation intuitive** : Menu de navigation avec indication de la page active
- **Formulaire de contact** : Formulaire accessible et validé côté client
- **Grille de produits** : Présentation visuelle des produits en vedette
- **Accessibilité** : Utilisation de balises sémantiques et attributs ARIA

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique avec balises modernes
- **CSS3** : Styles personnalisés avec Flexbox et Grid
- **JavaScript** : Scripts légers pour l'interactivité (année dynamique, etc.)
- **Google Fonts** : Police Inter pour une typographie moderne

## 📁 Structure du projet

```
fightfit.ietc/
│
├── index.html          # Page d'accueil
├── products.html       # Catalogue des produits
├── disciplines.html    # Présentation des disciplines
├── about.html          # À propos du magasin
├── contact.html        # Formulaire de contact
│
├── css/
│   ├── style.css       # Styles principaux
│   └── responsive.css  # Media queries pour le responsive
│
├── images/             # Images du site
│   ├── bandes.jpg
│   ├── gants.jpg
│   ├── michael-starkie-ynaiLpRBigY-unsplash.jpg
│   ├── protege-dents.jpg
│   ├── protège-tibia.jpg
│   ├── rashguard.jpg
│   ├── short.jpg
│   └── tibia.jpg
│
└── README.md           # Documentation du projet
```

## 🎯 Points techniques et pédagogiques

### HTML5 Sémantique
- Utilisation de balises sémantiques : `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- Attributs ARIA pour l'accessibilité
- Structure logique et hiérarchique

### CSS3 Moderne
- **Flexbox** : Pour la mise en page de l'en-tête, du hero et des formulaires
- **CSS Grid** : Pour les grilles de produits et les sections d'information
- **Media Queries** : Adaptation responsive avec breakpoints
  - Mobile : < 768px
  - Tablette : 768px - 1024px
  - Desktop : > 1024px

### Accessibilité
- Labels associés aux champs de formulaire
- Attributs `required` pour la validation
- Placeholders informatifs
- Navigation au clavier

## 🚀 Installation et lancement

### Option 1 : Ouvrir directement dans le navigateur
Double-cliquez sur `index.html` pour ouvrir le site dans votre navigateur par défaut.

### Option 2 : Serveur HTTP local (recommandé)

#### Avec Python
```bash
python -m http.server 8000
```
Puis ouvrez `http://localhost:8000` dans votre navigateur.

#### Avec Node.js
```bash
# Installation de http-server (une seule fois)
npm install -g http-server

# Lancement du serveur
http-server -p 8000
```

#### Avec PHP
```bash
php -S localhost:8000
```

### Option 3 : Extension VS Code
Installez l'extension "Live Server" dans VS Code et cliquez sur "Go Live" dans la barre d'état.

## 📱 Responsive Design

Le site est entièrement responsive et s'adapte à tous les types d'écrans :
- **Mobile** : Navigation optimisée, grilles en colonne unique
- **Tablette** : Mise en page adaptée aux écrans moyens
- **Desktop** : Expérience complète avec mise en page multi-colonnes

## 🎨 Personnalisation

Pour personnaliser le site :
1. Remplacez les images dans le dossier `images/` par vos propres visuels
2. Modifiez les couleurs dans `css/style.css` (variables CSS)
3. Ajustez le contenu texte directement dans les fichiers HTML
4. Personnalisez les breakpoints dans `css/responsive.css` si nécessaire

## 📝 Notes

- Les images utilisées sont des placeholders/exemples
- Le formulaire de contact nécessite un backend pour fonctionner complètement
- Le site est optimisé pour les navigateurs modernes (Chrome, Firefox, Safari, Edge)

## 📄 Licence

Ce projet est un exemple éducatif. Libre d'utilisation et de modification.

## 👤 Auteur

FightFit Store - Site vitrine pour magasin de sports de combat

---
