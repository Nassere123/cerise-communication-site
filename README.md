# CERISE COMMUNICATION & MARKETING - Site Web

Site vitrine professionnel pour CERISE COMMUNICATION & MARKETING, régie publicitaire en Côte d'Ivoire.

## 📁 Structure du Site

```
travel-agency-website/
├── index.html              # Page d'accueil
├── a-propos.html          # À propos de l'entreprise
├── services.html          # Nos domaines de compétences
├── reseau.html            # Réseau & couverture nationale
├── valeurs.html           # Nos 7 valeurs
├── partenaires.html       # Nos partenaires
├── perspectives.html      # Vision 2026-2028
├── contact.html           # Formulaire de contact
├── css/
│   ├── cerise-brand.css   # Styles principaux CERISE
│   └── navigation.css     # Navigation et footer
├── fonts/                 # Polices Google Fonts
└── images/                # Dossier pour vos images
```

## 🎨 Charte Graphique

- **Couleur principale:** Rouge cerise #DC143C
- **Couleurs secondaires:** Noir #1A1A1A, Blanc #FFFFFF
- **Typographies:** Montserrat (titres), Inter (texte)
- **Design:** Moderne, responsive, premium

## 🚀 Comment Ouvrir le Site

### Méthode 1 (Recommandée)
1. Double-cliquez sur `index.html`
2. Le site s'ouvre dans votre navigateur par défaut

### Méthode 2
1. Clic droit sur `index.html`
2. "Ouvrir avec" → Microsoft Edge (ou Chrome/Firefox)

### Méthode 3
1. Ouvrez votre navigateur
2. Appuyez sur Ctrl + O
3. Sélectionnez `index.html`

## 📄 Pages du Site

### 1. Accueil (index.html)
- Hero avec slogan "Votre Visibilité, Notre Expertise"
- Chiffres clés: 100+ panneaux, 200+ faces, 4 ans, +150M FCFA CA
- Aperçu des 4 services
- Carte de couverture nationale
- Logos partenaires

### 2. À propos (a-propos.html)
- Présentation SARL U (créée février 2022)
- 20 ans d'expérience du gérant
- Vision & ambition
- Positionnement stratégique

### 3. Services (services.html)
- **Panneaux publicitaires** - 12m² et Big Size 200m²
- **Gadgets publicitaires** - Sérigraphie, sublimation, DTF
- **Mobiliers urbains** - Conception, gestion, branding
- **Numérique & Décoration** - Branding, stands, supports

### 4. Réseau (reseau.html)
- Carte interactive Côte d'Ivoire
- **Abidjan:** Cocody, Marcory, Treichville, Yopougon, Abobo, Plateau
- **Intérieur:** Bouaké, Yamoussoukro, San Pedro, Soubré, Gagnoa

### 5. Valeurs (valeurs.html)
- Savoir-faire
- Créativité
- Réactivité
- Innovation
- Qualité
- Proximité client
- Intégrité

### 6. Partenaires (partenaires.html)
- SIB, LONACI, BETMOMO, UNFOLD
- Avantages du partenariat
- CTA "Devenir partenaire"

### 7. Perspectives (perspectives.html)
- Vision 2026-2028
- Panneaux numériques LED
- Réseau statique vs numérique

### 8. Contact (contact.html)
- Formulaire de contact complet
- Coordonnées
- Bouton WhatsApp
- Carte Google Maps (placeholder)

## ✏️ Personnalisation Nécessaire

### 1. Images à Ajouter
Placez vos images dans le dossier `images/` :

- **Hero:** Photo de panneau publicitaire CERISE
- **Services:** Photos de vos réalisations
- **Partenaires:** Logos réels (SIB, LONACI, BETMOMO, UNFOLD)
- **Équipe:** Photo de l'équipe ou du bureau

### 2. Coordonnées à Compléter

Dans **tous les fichiers HTML**, remplacez :

```
+225 XX XX XX XX XX  →  Votre vrai numéro
Abidjan, Côte d'Ivoire  →  Votre adresse complète
https://wa.me/225XXXXXXXXXX  →  Votre lien WhatsApp
```

### 3. Google Maps

Dans `contact.html`, remplacez le placeholder de carte par :
```html
<iframe 
  src="https://www.google.com/maps/embed?pb=VOS_COORDONNEES" 
  width="100%" 
  height="450" 
  style="border:0;" 
  allowfullscreen="" 
  loading="lazy">
</iframe>
```

## 📱 Responsive Design

Le site s'adapte automatiquement à :
- **Desktop:** 1366px et plus
- **Tablette:** 768px - 1365px
- **Mobile:** Moins de 768px

Menu hamburger automatique sur mobile.

## 🔧 Modifications Courantes

### Changer une Couleur
Ouvrez `css/cerise-brand.css` et modifiez :
```css
--cerise-red: #DC143C;  /* Changez cette valeur */
```

### Modifier le Texte
Ouvrez le fichier HTML correspondant et éditez directement le texte.

### Ajouter une Page
1. Dupliquez un fichier HTML existant
2. Modifiez le contenu
3. Ajoutez le lien dans le menu de navigation

## 📞 Support

Pour toute question sur le site :
- Consultez le fichier `walkthrough.md` dans le dossier `.gemini/antigravity/brain/`
- Vérifiez `task.md` pour la liste complète des fonctionnalités

## ✅ Checklist Avant Mise en Ligne

- [ ] Remplacer toutes les images placeholder
- [ ] Compléter les coordonnées (téléphone, adresse)
- [ ] Intégrer Google Maps
- [ ] Ajouter les vrais logos partenaires
- [ ] Tester sur mobile
- [ ] Vérifier tous les liens
- [ ] Tester le formulaire de contact

---

**Créé le:** 4 février 2026  
**Version:** 1.0  
**Statut:** Prêt pour personnalisation
