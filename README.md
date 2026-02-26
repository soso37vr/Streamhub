<div align="center">

<br/>

```
 ██████╗████████╗██████╗ ███████╗ █████╗ ███╗   ███╗    ██╗  ██╗██╗   ██╗██████╗ 
██╔════╝╚══██╔══╝██╔══██╗██╔════╝██╔══██╗████╗ ████║    ██║  ██║██║   ██║██╔══██╗
╚█████╗    ██║   ██████╔╝█████╗  ███████║██╔████╔██║    ███████║██║   ██║██████╔╝
 ╚═══██╗   ██║   ██╔══██╗██╔══╝  ██╔══██║██║╚██╔╝██║    ██╔══██║██║   ██║██╔══██╗
██████╔╝   ██║   ██║  ██║███████╗██║  ██║██║ ╚═╝ ██║    ██║  ██║╚██████╔╝██████╔╝
╚═════╝    ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝    ╚═╝  ╚═╝ ╚═════╝ ╚═════╝ 
```

**Tous vos services de streaming au même endroit — rapide, propre, légal.**

<br/>

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Framework](https://img.shields.io/badge/No_Framework-000000?style=for-the-badge&logo=circle&logoColor=white)]()
[![License MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)]()

<br/>

![StreamHub Preview](https://img.shields.io/badge/▶_Live_Demo-Ouvrir_dans_le_navigateur-e63946?style=for-the-badge)

<br/>

</div>

---

## 📖 À propos

**StreamHub** est une application web minimaliste et moderne qui regroupe tous vos services de streaming sur une seule page. Fini de jongler entre Netflix, Disney+, Prime Video et les autres — un seul endroit pour tout centraliser.

> ⚠️ **StreamHub est un simple lanceur de liens.** Il ne stocke aucun identifiant, ne contourne aucun DRM et ne viole aucune condition d'utilisation. Chaque service s'ouvre dans un nouvel onglet où vous vous connectez normalement avec votre propre compte.

---

## ✨ Fonctionnalités

### 🎬 Hero Carousel — Films à la une
- Présentation cinématographique en plein-écran du contenu phare de chaque plateforme
- **Rotation automatique** configurable (10 à 30 secondes)
- Affiche animée avec dégradé de couleurs unique par service
- Navigation manuelle via les points en bas

### 📺 Bande-annonces YouTube
- Bouton **"Bande-annonce"** sur chaque slide du hero → redirige vers YouTube
- Icône YouTube sur chaque titre dans les cartes → recherche directe du trailer
- Aucune API requise, fonctionne hors-ligne

### 🃏 Cartes de service enrichies
- Mini-affiches colorées pour chaque titre à l'affiche
- 4 contenus recommandés par plateforme avec genre et année
- Effet shimmer au survol
- Animation de particules au clic

### 🎨 Personnalisation complète
- **64 couleurs d'accent** différentes
- **8 thèmes prédéfinis** : Cinéma, Néon, Glacé, Forêt, Coucher de soleil, Minuit, Royal, Feu
- Curseur de l'intensité de la lueur
- Panneau de paramètres accessible en un clic

### ⚡ Performance
- **Aucune dépendance** — HTML, CSS, JS vanilla pur
- **Fichier unique** — 1 seul `.html` à ouvrir
- Chargement instantané, aucun serveur nécessaire

---

## 🚀 Installation & Utilisation

### Méthode 1 — Locale (recommandée)

```bash
# Cloner le dépôt
git clone https://github.com/votre-username/streamhub.git

# Ouvrir le fichier
cd streamhub
open index.html   # macOS
xdg-open index.html  # Linux
start index.html  # Windows
```

### Méthode 2 — GitHub Pages

```bash
# 1. Forker ce dépôt
# 2. Aller dans Settings → Pages
# 3. Source : Deploy from branch → main → / (root)
# 4. Votre StreamHub sera accessible sur :
#    https://votre-username.github.io/streamhub
```

### Méthode 3 — Téléchargement direct

Télécharger `index.html` → Double-cliquer → C'est tout. ✅

---

## 📂 Structure du projet

```
streamhub/
│
├── index.html          # Application complète (tout-en-un)
├── README.md           # Ce fichier
└── LICENSE             # Licence MIT
```

> Le projet est intentionnellement un fichier unique. Pas de build, pas de npm, pas de config.

---

## 📡 Services inclus

| Service | Plateforme | Lien |
|---------|-----------|------|
| 🔴 Netflix | Mondial | [netflix.com](https://www.netflix.com) |
| 🔵 Disney+ | Mondial | [disneyplus.com](https://www.disneyplus.com) |
| 🔷 Prime Video | Amazon | [primevideo.com](https://www.primevideo.com) |
| ⬛ Apple TV+ | Apple | [tv.apple.com](https://tv.apple.com) |
| 🟣 Max | Warner/HBO | [max.com](https://www.max.com) |
| 🟢 Hulu | États-Unis | [hulu.com](https://www.hulu.com) |
| 🔵 Paramount+ | Paramount | [paramountplus.com](https://www.paramountplus.com) |
| ⬜ Canal+ | France | [canalplus.com](https://www.canalplus.com) |

---

## 🖥️ Captures d'écran

<div align="center">

### Hero — Contenu à la une
```
┌─────────────────────────────────────────────────────────┐
│  [Netflix]                           ╔═══════════════╗  │
│                                      ║               ║  │
│  Squid Game Saison 2                 ║    🦑         ║  │
│  Thriller · 2024 · ★ 8.0             ║               ║  │
│                                      ║               ║  │
│  Les Jeux reprennent...              ╚═══════════════╝  │
│                                                         │
│  [▶ Regarder]  [▶ Bande-annonce]                        │
│                                                         │
│  • • • • • • • •                          ▓▓▓░░░░░░░░  │
└─────────────────────────────────────────────────────────┘
```

### Cartes de services
```
┌──────────────────┐  ┌──────────────────┐
│ ████████████████ │  │ ████████████████ │
│  [N]  Netflix    │  │ [D+]  Disney+    │
├──────────────────┤  ├──────────────────┤
│ À voir maintenant│  │ À voir maintenant│
│ 🦑 Squid Game   ▶│  │ 🔮 Agatha       ▶│
│ 🔦 Stranger Thi ▶│  │ ⚡ X-Men '97    ▶│
│ 🏛️ The Diplomat ▶│  │ 🌊 Moana 2      ▶│
│ 📱 Black Mirror ▶│  │ ⚔️ The Acolyte  ▶│
│                  │  │                  │
│ [Ouvrir Netflix→]│  │[Ouvrir Disney+ →]│
└──────────────────┘  └──────────────────┘
```

</div>

---

## ⚙️ Personnalisation

### Ajouter un service

Dans `index.html`, ajouter un objet dans le tableau `SERVICES` :

```javascript
{
  id: 'monservice',
  name: 'Mon Service',
  url: 'https://www.monservice.com',
  logo: 'MS',
  logoBg: '#FF6600',
  logoText: '#fff',
  gradA: '#FF6600',
  gradB: '#993D00',
  heroTitle: 'Titre du film vedette',
  heroSpan: 'Sous-titre',
  heroMeta: ['Genre', '2024'],
  heroScore: '8.5',
  heroDesc: "Description courte du contenu mis en avant.",
  heroColor: '#FF6600',
  trailerQ: 'titre+film+trailer+officiel',
  posterEmoji: '🎬',
  posterGrad: 'linear-gradient(145deg, #993D00, #FF6600)',
  shows: [
    {
      name: 'Titre 1',
      sub: 'Genre · Année',
      emoji: '🎬',
      grad: 'linear-gradient(145deg, #993D00, #FF6600)',
      yt: 'titre+1+trailer'
    },
    // ...
  ]
}
```

### Changer la couleur par défaut

```javascript
// Ligne ~290 dans le script
let currentColor = '#e63946';  // ← Changer ici
```

### Modifier l'intervalle de rotation par défaut

```javascript
let heroInterval = 15000;  // ← En millisecondes (15 secondes)
```

---

## 🔒 Confidentialité & Légalité

- ✅ **Aucun stockage de données** — ni cookies, ni localStorage, ni base de données
- ✅ **Aucune collecte d'informations** — StreamHub ne sait pas qui vous êtes
- ✅ **Aucun contournement** — chaque plateforme gère elle-même l'authentification
- ✅ **Open source** — le code est entièrement lisible et auditable
- ✅ **Liens directs** — StreamHub est l'équivalent d'un dossier de favoris amélioré

---

## 🛠️ Technologies

| Technologie | Usage |
|-------------|-------|
| **HTML5** | Structure de l'application |
| **CSS3** | Animations, variables, grid, backdrop-filter |
| **JavaScript ES6+** | Logique, carousel, effets visuels |
| **Google Fonts** | Syne (titres) + DM Sans (texte) |
| **YouTube** | Recherche de bandes-annonces (aucune API) |

**Aucune dépendance externe** au-delà des Google Fonts.

---

## 🤝 Contribuer

Les contributions sont les bienvenues !

```bash
# 1. Forker le projet
# 2. Créer une branche
git checkout -b feature/nouveau-service

# 3. Commiter vos changements
git commit -m "feat: ajout de Crunchyroll"

# 4. Push et Pull Request
git push origin feature/nouveau-service
```

### Idées de contributions
- [ ] Ajouter d'autres services (Crunchyroll, Mubi, Salto...)
- [ ] Mode clair / thème jour
- [ ] Sauvegarde des préférences en localStorage
- [ ] Support PWA (Progressive Web App)
- [ ] Version avec une vraie API TMDB pour les vraies affiches

---

## 📄 Licence

```
MIT License — Vous pouvez utiliser, modifier et distribuer ce projet librement.
Les logos et marques des services de streaming appartiennent à leurs propriétaires respectifs.
```

---

<div align="center">

Fait avec ❤️ · **StreamHub** — Votre télécommande universelle du streaming

<br/>

*Si ce projet vous est utile, n'hésitez pas à lui donner une ⭐ sur GitHub !*

</div>
