# ARCHITEKT - Site Web d'Architecture

## 🏗️ Description

Site web sophistiqué pour une entreprise d'architecture extérieure, créé en HTML/CSS/JS pur avec des effets visuels avancés et des transitions fluides.

## ✨ Fonctionnalités

### Design & Esthétique
- **Typographies premium** : Montserrat (ultra-light), Crimson Text, Source Sans Pro
- **Effet parallax avancé** : Image hero fixe avec contenu qui glisse par-dessus
- **Animations sophistiquées** : Cubic-bezier, fade-in, scale effects
- **Glass morphism** : Effets de transparence et blur modernes
- **Couleurs architecturales** : Palette or/ambre et gris

### Pages Incluses
- ✅ **index.html** - Page d'accueil avec parallax
- ✅ **services.html** - Services détaillés avec processus
- ✅ **contact.html** - Formulaire de contact et informations
- 🔄 **projets.html** - Portfolio de réalisations (à créer)
- 🔄 **about.html** - À propos de l'entreprise (à créer)

### Effets Spéciaux
- **Scroll parallax** : L'image reste fixe, le contenu glisse
- **Header dynamique** : Transparent → Glass morphism au scroll
- **Navigation mobile** : Menu hamburger avec animations
- **Animations au scroll** : Éléments qui apparaissent progressivement
- **Hover effects** : Transformations 3D sophistiquées

## 🚀 Installation

1. **Téléchargez tous les fichiers** dans un dossier
2. **Ouvrez `index.html`** dans votre navigateur
3. **C'est tout !** Le site fonctionne immédiatement

## 📁 Structure des Fichiers

```
/
├── index.html          # Page d'accueil avec effet parallax
├── services.html       # Page des services
├── contact.html        # Page de contact
├── style.css          # Tous les styles CSS
├── script.js          # Toute la logique JavaScript
└── README.md          # Ce fichier
```

## 🎨 Personnalisation

### Colors (dans style.css)
```css
/* Couleur principale */
#d4af37 (or/ambre)

/* Couleur secondaire */
#f4d03f (or clair)

/* Texte */
#333 (gris foncé)
#666 (gris moyen)
```

### Fonts
- **Titres** : Montserrat (weight: 100-900)
- **Texte élégant** : Crimson Text
- **Texte courant** : Source Sans Pro

### Images
Remplacez les URLs Unsplash par vos propres images :
```html
<!-- Dans index.html -->
background-image: url('votre-image-hero.jpg')

<!-- Dans les cards projets -->
<img src="votre-projet-1.jpg" alt="Votre Projet">
```

## 📱 Responsive

Le site s'adapte automatiquement :
- **Desktop** : Mise en page complète
- **Tablet** : Grilles adaptées
- **Mobile** : Menu hamburger, colonnes simples

## ⚡ Performance

- **CSS pur** : Pas de frameworks lourds
- **Images optimisées** : Lazy loading inclus
- **Animations performantes** : GPU-accelerated
- **Code minimaliste** : Chargement rapide

## 🛠️ Personnalisation Avancée

### Modifier le contenu
1. Ouvrez les fichiers HTML
2. Changez les textes directement
3. Remplacez les images par les vôtres

### Ajouter des pages
1. Copiez `services.html`
2. Renommez le fichier
3. Modifiez le contenu
4. Ajoutez le lien dans la navigation

### Modifier les animations
Dans `style.css`, cherchez :
```css
.animate-fade-in-up {
    /* Modifiez la durée, le timing, etc. */
}
```

## 🌐 Hébergement

Le site peut être hébergé sur :
- **GitHub Pages** (gratuit)
- **Netlify** (gratuit) 
- **Vercel** (gratuit)
- **Tout hébergeur web** classique

### Déploiement GitHub Pages
1. Créez un repo GitHub
2. Uploadez tous les fichiers
3. Activez GitHub Pages dans Settings
4. Votre site sera accessible !

## 📞 Support

Pour toute question ou personnalisation :
- Modifiez directement les fichiers HTML/CSS/JS
- Utilisez les commentaires dans le code comme guide
- Testez les changements en rafraîchissant votre navigateur

## 🎯 Fonctionnalités Avancées Incluses

- ✅ Formulaire de contact fonctionnel (côté client)
- ✅ Animations d'intersection (Intersection Observer)
- ✅ Debounced scroll events (optimisation)
- ✅ Back-to-top button automatique
- ✅ Lazy loading pour les images
- ✅ Navigation keyboard-friendly
- ✅ Console branding message

---

**🎉 Votre site ARCHITEKT est prêt !** 

Professionnel, moderne et entièrement personnalisable selon vos besoins.