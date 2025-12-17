# 1001 Concepts - Site Vitrine

Site vitrine professionnel pour 1001 Concepts Isolation Thermique par Extérieur.

## 🚀 Structure du Projet

```
├── index.html          # Page principale
├── styles.css          # Styles CSS
├── script.js           # JavaScript
└── README.md           # Documentation
```

## ✨ Fonctionnalités

- ✅ Design moderne et responsive
- ✅ Navigation fixe avec menu mobile
- ✅ Section Hero avec CTA
- ✅ Services détaillés (ITE, Bardage, Façades)
- ✅ Section "Pourquoi nous choisir"
- ✅ Portfolio de réalisations
- ✅ Avis clients Google (vrais avis)
- ✅ Formulaire de contact
- ✅ Animations au scroll
- ✅ 100% responsive (mobile, tablette, desktop)

## 📱 Sections

1. **Header** - Navigation fixe avec logo et menu
2. **Hero** - Bannière d'accueil avec CTA
3. **Services** - 3 services principaux
4. **Pourquoi nous choisir** - 4 arguments clés
5. **Réalisations** - Portfolio de projets
6. **Avis Clients** - Vrais avis Google
7. **Contact** - Formulaire + coordonnées
8. **Footer** - Navigation + infos

## 🎨 Palette de Couleurs

- Primaire: `#2563eb` (Bleu)
- Secondaire: `#1e40af` (Bleu foncé)
- Accent: `#f59e0b` (Orange)
- Succès: `#10b981` (Vert)

## 🔧 Personnalisation

### Modifier les couleurs
Éditer les variables CSS dans `styles.css` :
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... */
}
```

### Modifier le contenu
Tout le contenu est dans `index.html` - super facile à modifier.

### Ajouter des images
Remplace les gradients dans la section réalisations par de vraies images :
```html
<div class="realisation-image" style="background-image: url('images/projet1.jpg');">
```

## 📧 Formulaire de Contact

Le formulaire est fonctionnel mais nécessite un backend pour envoyer les emails.

**Options d'intégration :**

1. **Formspree** (gratuit)
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

2. **EmailJS** (gratuit)
Ajoute le SDK et configure l'envoi d'emails.

3. **Backend PHP**
Crée un fichier `send-email.php` pour traiter le formulaire.

## 🚀 Déploiement

### Option 1 : Hébergement Classique
1. Upload tous les fichiers sur ton serveur FTP
2. Assure-toi que `index.html` est à la racine
3. C'est prêt !

### Option 2 : Netlify (Gratuit)
1. Drag & drop du dossier sur netlify.com
2. Configuration automatique
3. URL gratuite + SSL

### Option 3 : GitHub Pages (Gratuit)
1. Push le code sur GitHub
2. Active GitHub Pages dans les settings
3. Site disponible sur `username.github.io/repo`

## ✅ Checklist avant mise en ligne

- [ ] Ajouter de vraies photos des réalisations
- [ ] Configurer le formulaire de contact
- [ ] Ajouter un favicon (`<link rel="icon" href="favicon.ico">`)
- [ ] Vérifier tous les liens
- [ ] Tester sur mobile
- [ ] Optimiser les images
- [ ] Ajouter Google Analytics (optionnel)
- [ ] Ajouter un sitemap.xml pour le SEO

## 📈 SEO & Performance

Le site est optimisé pour :
- ✅ Référencement naturel (balises meta, structure H1-H6)
- ✅ Performance (CSS/JS optimisés)
- ✅ Accessibilité (structure sémantique)
- ✅ Mobile-first (responsive design)

## 💡 Améliorations Futures

- Galerie photos avec lightbox
- Intégration Google Maps
- Blog pour le SEO
- Chatbot ou chat en direct
- Espace client
- Calculateur de devis en ligne

## 📞 Support

Pour toute question ou modification, contacte-moi !

---

**Note:** Les avis clients sont les vrais avis Google de l'entreprise. Le site est prêt à l'emploi, il suffit juste d'ajouter de vraies photos des réalisations et de configurer l'envoi du formulaire.