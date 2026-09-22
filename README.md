# 📧 Mail Clicker — Nuit MMI 2025

Un **jeu clicker** (type *Cookie Clicker*) et sa landing page, sur le thème de la **pollution numérique**. Le but : vider sa boîte mail en supprimant des emails inutiles, et découvrir au passage combien de CO₂ cela représente. 

Créé en **moins de 24 heures** lors de la Nuit MMI 2025 (IUT du Limousin) en équipe de 3.
(Le jeu comporte donc des anomalies et n'est pas terminé)

---

## 🎮 Le jeu

- Chaque clic supprime des emails ; chaque email supprimé évite **environ 4 g de CO₂**, et un compteur affiche le total en g, kg puis tonnes.
- Les emails gagnés permettent d'acheter des **générateurs passifs** (feuille, pousse, buisson, arbre, forêt) qui suppriment des emails automatiquement.
- Des **boosts** accélèrent la progression : plus d'emails par clic, auto-clic, multiplicateur, bonus de 15 %.
- Des **notifications pédagogiques** se déclenchent à certains paliers et comparent le CO₂ évité à des gestes du quotidien : une douche de 10 minutes, 100 Go stockés dans le cloud pendant un an, un vol Paris–Berlin…

L'idée : sensibiliser à l'impact environnemental des emails de façon ludique, sans être moralisateur.

---

## 📁 Contenu du repo

```
├── Jeu-Nuit-MMI/   → le jeu (p5.js)
└── LandingPage/    → la page de présentation du jeu
```

## 🛠️ Stack technique

- **p5.js** (et p5.sound) — rendu, boucle de jeu, interactions et sons
- **JavaScript** — logique de jeu (économie, générateurs, boosts, paliers)
- **HTML / CSS** — interface et landing page

---

## 🚀 Lancer le projet

Le jeu charge ses SVG via `fetch`, il faut donc passer par un petit serveur local :

```bash
git clone https://github.com/BradSavary/Nuit-MMI.git
cd Nuit-MMI
npx serve .
```

Puis ouvre `/Jeu-Nuit-MMI` pour le jeu, ou `/LandingPage` pour la landing page.

---

## 👤 Auteur

**Brad Savary** — [Portfolio](https://bradsavary.dev) · [LinkedIn](https://www.linkedin.com/in/brad-savary-07322b294/)
