# Portfolio Moderne - Développeur & Designer

[My Portfolio](https://p13rrick.github.io/Portfolio-PierrickB/)

Un portfolio personnel moderne, interactif et animé, conçu avec HTML, CSS et JavaScript vanilla. Inspiré des meilleurs portfolios primés sur Awwwards, ce site allie esthétique premium et performance.

## 🎨 Style & Design

### Direction Artistique
- **Style** : Minimaliste dark, futuriste et entrepreneur
- **Inspiration** : Awwwards, Apple Design
- **Palette de couleurs** :
  - Violet clair (`#8B5CF6`) - Couleur primaire
  - Bleu ciel (`#38BDF8`) - Couleur secondaire
  - Blanc (`#FFFFFF`) - Accents et texte
  - Fond dark (`#0A0A0F`) - Base sombre premium

### Typographie
- **Police principale** : Inter (moderne, lisible)
- **Police display** : Space Grotesk (expressive, distinctive)
- Hiérarchie typographique claire avec des tailles responsives

## 🏗️ Architecture

### Structure HTML
```
index.html
├── Navigation fixe (navbar)
├── Hero Section (section d'accueil impactante)
├── À propos (présentation personnelle)
├── Projets (portfolio de réalisations)
├── Compétences (expertise technique)
├── Contact (formulaire et informations)
└── Footer
```

### Organisation CSS
Le CSS est organisé en sections logiques :
1. **Variables CSS** : Toutes les couleurs, espacements et valeurs réutilisables
2. **Reset & Base** : Normalisation et styles de base
3. **Composants** : Navigation, boutons, cartes, formulaires
4. **Sections** : Styles spécifiques à chaque section
5. **Animations** : Keyframes et transitions
6. **Responsive** : Media queries pour mobile/tablette/desktop

### JavaScript Modulaire
Le JavaScript est structuré en modules fonctionnels :
- **Curseur personnalisé** : Suivi fluide de la souris
- **Navigation** : Scroll effects, menu mobile, liens actifs
- **Animations au scroll** : Intersection Observer API
- **Micro-interactions** : Hover effects, transitions
- **Formulaires** : Validation et animations
- **Performance** : Optimisations et lazy loading

## ✨ Fonctionnalités

### Animations & Interactions

1. **Hero Section**
   - Animation d'entrée séquentielle des éléments
   - Orbes de gradient animés en arrière-plan
   - Carte flottante avec effet de profondeur
   - Indicateur de scroll animé

2. **Navigation**
   - Navbar qui change au scroll
   - Menu mobile avec animation hamburger
   - Liens actifs selon la section visible
   - Smooth scroll vers les sections

3. **Projets**
   - Grille responsive avec overlay au hover
   - Animation de zoom sur les images
   - Tags et informations au survol
   - Transitions fluides

4. **Compétences**
   - Barres de progression animées au scroll
   - Effet shimmer sur les barres
   - Compteurs animés pour les statistiques

5. **Contact**
   - Formulaire avec labels flottants
   - Validation et feedback visuel
   - Liens sociaux avec micro-animations

6. **Curseur personnalisé**
   - Curseur principal et follower
   - Effets hover sur les éléments interactifs
   - Désactivé automatiquement sur mobile

### Responsive Design
- **Desktop** : Layout en grille, animations complètes
- **Tablette** : Adaptation des colonnes, menu mobile
- **Mobile** : Stack vertical, optimisations tactiles

## 🚀 Utilisation

### Installation
Aucune installation requise ! Le portfolio fonctionne directement :
1. Ouvrez `index.html` dans un navigateur moderne
2. Ou servez les fichiers via un serveur local (recommandé)

### Personnalisation

#### Couleurs
Modifiez les variables CSS dans `styles.css` :
```css
:root {
    --color-primary: #8B5CF6;
    --color-secondary: #38BDF8;
    /* ... */
}
```

#### Contenu
- Remplacez les textes dans `index.html`
- Ajoutez vos projets dans la section projets
- Modifiez les compétences et statistiques
- Mettez à jour les informations de contact

#### Images
- Remplacez les placeholders par vos propres images
- Ajoutez des images de projets dans les `.project-thumbnail`
- Personnalisez l'image de profil dans `.about-image`

## 🎯 Choix Techniques

### Pourquoi Vanilla JS ?
- **Performance** : Pas de surcharge de framework
- **Légèreté** : Chargement rapide
- **Contrôle total** : Animations personnalisées
- **Maintenabilité** : Code simple et direct

### Optimisations
- **Intersection Observer** : Animations performantes au scroll
- **RequestAnimationFrame** : Animations fluides du curseur
- **CSS Variables** : Maintenance facile des styles
- **Lazy loading** : Chargement optimisé des animations

### Accessibilité
- Navigation au clavier
- Labels de formulaire accessibles
- Contraste de couleurs respecté
- Structure sémantique HTML5

## 📱 Compatibilité

- ✅ Chrome/Edge (dernières versions)
- ✅ Firefox (dernières versions)
- ✅ Safari (dernières versions)
- ✅ Mobile (iOS Safari, Chrome Mobile)

## 🔧 Technologies Utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Flexbox, Grid, Variables, Animations
- **JavaScript ES6+** : Vanilla JS moderne
- **Google Fonts** : Inter & Space Grotesk

## 📝 Notes de Développement

### Points d'attention
- Les animations utilisent `transform` et `opacity` pour de meilleures performances
- Le curseur personnalisé est désactivé sur mobile pour éviter les conflits
- Les animations au scroll utilisent l'Intersection Observer pour l'efficacité
- Le formulaire de contact nécessite une intégration backend pour fonctionner

### Améliorations possibles
- Intégration d'un backend pour le formulaire de contact
- Ajout d'un mode clair/sombre
- Intégration de Three.js pour des effets 3D
- Ajout d'un blog ou d'une section articles
- Optimisation SEO avancée

## 📄 Licence

Ce portfolio est libre d'utilisation et de modification pour vos projets personnels.

---

**Créé avec passion pour l'esthétique et la performance** ✨

