# 🍽️ 24LeRestaurant — Site Web

Site vitrine d'un restaurant parisien fictif situé au pied des Champs-Élysées, réalisé en HTML/CSS vanilla.

---

## 📋 Description

**24LeRestaurant** est un site web multi-pages conçu pour présenter un restaurant gastronomique parisien. Il propose une navigation fluide entre les différentes sections : accueil, menu, horaires et contact, avec un design responsive adapté aux mobiles.

---

## 📁 Structure du projet

```
projet/
│
├── recette.acceuil.html       # Page d'accueil
├── recette.Menu.html          # Page Menu & Carte
├── recette.horaires.html      # Page Horaires & Réservation
├── recette.contact.html       # Page Contact
│
├── recette.acceuil.css        # Styles de la page Accueil
├── recette.Menu.css           # Styles de la page Menu
├── recette.horraire.css       # Styles de la page Horaires
├── recette.contact.css        # Styles de la page Contact
│
└── img_resto/                 # Dossier des images et icônes
    ├── icons8-menu.svg
    ├── icons8-close.svg
    ├── icons8-youtube.svg
    ├── icons8-instagram.svg
    ├── icons8-facebook.svg
    ├── mail.png
    ├── telephone (1).png
    └── circle.png
```

---

## 🗂️ Pages

### 🏠 Accueil — `recette.acceuil.html`
- Image hero avec bouton de réservation
- Présentation du restaurant et du chef
- Grille de plats vedettes
- Section avis clients
- Footer avec informations et réseaux sociaux

### 🍴 Menu — `recette.Menu.html`
- Présentation du menu déjeuner saisonnier (42€)
- Entrée, plat et dessert du jour
- Carte complète : entrées, plats, desserts avec prix

### 🕐 Horaires — `recette.horaires.html`
- Tableau des horaires d'ouverture
- Formulaire de contact (prénom, nom, e-mail, message)
- Carte interactive **Leaflet.js** centrée sur le restaurant

### 📞 Contact — `recette.contact.html`
- Informations de contact : email, téléphone, adresse
- Adresse : 24 rue Antoinette Besson, 75008 Paris
- Téléphone : 01 42 25 38 25

---

## 🎨 Design & Style

| Élément | Valeur |
|---|---|
| Couleur principale | `#A78963` (beige doré) |
| Couleur secondaire | `#224d4d` (vert foncé) |
| Fond footer | `#05090E` (noir) |
| Police titres | Libre Baskerville |
| Police texte | Raleway |

---

## 📱 Responsive Design

Le site est entièrement responsive avec deux breakpoints :

- **≤ 1232px** : navigation burger, mise en page adaptée en colonne
- **≤ 430px** : sidebar en pleine largeur sur mobile

La navigation mobile utilise une **sidebar** latérale déclenchée par un menu burger (JS vanilla).

---

## 🛠️ Technologies utilisées

- **HTML5**
- **CSS3** (Flexbox, Grid, Media Queries)
- **JavaScript** vanilla (sidebar mobile)
- **Leaflet.js** `v1.7.1` — carte interactive OpenStreetMap
- **Google Fonts** — Libre Baskerville & Raleway

---

## 🚀 Lancement

Aucune installation requise. Il suffit d'ouvrir le fichier HTML dans un navigateur :

```bash
# Ouvrir directement dans le navigateur
open recette.acceuil.html
```

Ou utiliser l'extension **Live Server** sur VS Code pour un rechargement automatique.

---

## Crédits

- Icônes : [Icons8](https://icons8.com)
- Carte : [OpenStreetMap](https://www.openstreetmap.org) via Leaflet.js
- Logo : [24lerestaurant.fr](https://24lerestaurant.fr)

---

© 24 le Restaurant — 24 rue Jean Mermoz, 75008 Paris — 2024
