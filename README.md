# Alpes'Air Thermique — Site vitrine

Site vitrine de l'activité artisanale **Alpes'Air Thermique** (électricité, climatisation, PAC, plomberie) en Auvergne-Rhône-Alpes.

## Stack technique
- HTML5 statique (zéro dépendance, zéro framework)
- CSS custom properties (charte bleue/verte/ambre)
- Google Fonts : Playfair Display + DM Sans
- Formspree pour le formulaire de contact
- Hébergement : Render (free tier)

## Structure
```
alpesair-thermique/
├── index.html              ← Page principale (accueil)
├── mentions-legales.html   ← Mentions légales RGPD
├── assets/
│   ├── hero.webp           ← Photo chalet + logo (hero)
│   └── electricite.webp    ← Icône électricité verte
└── README.md
```

## Déploiement Render
1. Connecter ce repo GitHub à Render
2. **Build command :** *(vide)*
3. **Publish directory :** `.` (racine)
4. Root directory : *(vide)*

## À compléter avant mise en ligne
- [ ] Remplacer `YOUR_FORM_ID` dans `index.html` par l'ID Formspree
- [ ] Compléter les mentions légales (SIRET, adresse, assureur)
- [ ] Domaine personnalisé : `alpesair-thermique.fr` (OVH)
- [ ] Email pro : `contact@alpesair-thermique.fr`

## Charte couleurs
| Variable CSS       | Valeur    | Usage                  |
|--------------------|-----------|------------------------|
| `--bleu-nuit`      | `#0B1E3D` | Fond nav, sections dark|
| `--bleu-roi`       | `#1A4A8A` | Accents bleu           |
| `--bleu-ciel`      | `#2E7DD1` | Liens, accents         |
| `--vert-alpin`     | `#2EAB6E` | Badges actifs, icônes  |
| `--ambre`          | `#F0A500` | CTA, highlights        |
