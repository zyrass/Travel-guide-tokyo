# 🇯🇵 Travel Guide - Tokyo

<p align="center">
  <a href="https://zyrass.github.io/Travel-guide-tokyo/">
    <img src="https://img.shields.io/badge/Module-D12_Integration-FF4800?style=for-the-badge&logo=html5&logoColor=white" alt="Module D12" />
  </a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <a href="https://zyrass.github.io/Travel-guide-tokyo/">
    <img src="https://img.shields.io/badge/GitHub_Pages-deployed-222222?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages" />
  </a>
  <img src="https://img.shields.io/badge/Dur%C3%A9e-1_Apr%C3%A8s--midi-brightgreen?style=for-the-badge" alt="Durée 1 Après-midi" />
</p>

<p align="center">
  <img src="./assets/images/city-night-view-g75b82b18a_1920.jpg" alt="Tokyo Night View Banner" width="100%" style="border-radius: 8px; box-shadow: 0 10px 30px rgba(0,0,0,0.25);" />
</p>

---

## ⚡ Le Défi : Intégration en un Temps Record !

Ce projet est un **TP d'intégration intensif** réalisé en **une seule après-midi** dans le cadre du module **D12 (Consolidation des compétences en intégration web : HTML / CSS / UX)**. 

L'objectif principal était de concevoir et d'intégrer une page vitrine complète, fluide et responsive pour tester notre rapidité d'exécution et notre maîtrise des technologies d'intégration web modernes sans framework.

> [!TIP]
> **Performance sous contrainte :** Concevoir une architecture sémantique, gérer une grille adaptative complexe, créer une galerie interactive et assurer la fluidité de la mise en page en moins de 4 heures témoigne d'une grande maîtrise opérationnelle.

---

## 🚀 Fonctionnalités & Expérience Utilisateur

* **Grille Responsive Avancée :** Conception d'une interface s'adaptant parfaitement aux smartphones, tablettes et grands écrans d'ordinateur.
* **Layout Adaptatif :** Inversion alternée des sections d'activités (images et textes alternés à gauche/droite) sur les écrans plus larges pour briser la monotonie visuelle.
* **Galerie Interactive :** Grille d'images fluide utilisant des effets de mise au point progressive et de zoom fluide lors du survol.
* **Design System Épuré :** Palette de couleurs contrastée s'appuyant sur des variables CSS personnalisées (`--primary`, `--secondary`, etc.).
* **Focalisation Numéros d'Urgence :** Section d'aide pour les voyageurs contenant les numéros indispensables de Tokyo.

---

## 🛠️ Pile Technologique & Architecture

Le projet est entièrement construit selon les standards modernes du web, sans bibliothèques ni frameworks externes :

* **HTML5 Sémantique :** Utilisation rigoureuse des balises de structure (`<header>`, `<main>`, `<section>`, `<figure>`, `<footer>`, `<nav>`) pour garantir un excellent référencement naturel (SEO) et une accessibilité optimale.
* **CSS3 Moderne :**
  - **CSS Grid :** Utilisé pour la structure globale de la page (`body`), ainsi que pour la grille dynamique de la galerie de photos.
  - **Flexbox :** Utilisé pour l'alignement précis des cartes d'activité, des boutons de navigation et du footer.
  - **Media Queries :** Breakpoints progressifs assurant une compatibilité mobile-first et desktop de manière fluide.

---

## 💎 Refonte & Optimisations Majeures

Afin d'élever ce projet étudiant à un niveau de **production professionnelle**, le code a subi des optimisations majeures :

1. **Correction du Bug du Footer (CSS Grid) :** Les pistes de hauteur figées de la grille principale ont été remplacées par des valeurs dynamiques (`auto`). Cela résout définitivement les chevauchements et débordements d'éléments qui survenaient sur tablette et ordinateur.
2. **Correction des Données Géographiques (Contenu) :** Remplacement des numéros d'urgence thaïlandais (copy-paste de Bangkok) par les véritables coordonnées et numéros de sécurité du Japon (Police : `110`, Pompiers : `119`, Japan Helpline).
3. **Typographies Premium (Identité Visuelle) :** Importation et déploiement de **Google Fonts** :
   - **Outfit** (Linéale géométrique ultra-moderne pour le corps et la structure).
   - **Playfair Display** (Empattement élégant pour donner un accent traditionnel et premium aux titres japonais).
4. **Micro-interactions Dynamiques :** Ajout de transitions CSS douces (`transition: all 0.3s ease`) sur l'échelle des cartes, l'ombrage, la désaturation progressive des photographies et l'agrandissement pop des icônes de réseaux sociaux au survol.
5. **Accessibilité (a11y) & SEO Hardening :** Intégration de balises `alt` descriptives pour chacune des images de la galerie et des cartes, et changement de la déclaration de langue principale en français (`lang="fr"`).

---

## 📂 Structure du Projet

```bash
Travel-guide-tokyo/
├── index.html            # Squelette et contenu du guide (HTML5)
├── README.md             # Ce guide de présentation premium
└── assets/
    ├── styles/
    │   └── style.css     # Feuilles de styles, grille responsive et animations
    └── images/
        ├── facebook.png
        ├── twitter.png
        ├── symbole-google-plus.png
        └── [17 photos haute résolution de Tokyo]
```

---

## 🌐 Déploiement en Ligne

Le site est hébergé de manière permanente et mis à jour automatiquement via GitHub Pages :
👉 **[Accéder au site en direct](https://zyrass.github.io/Travel-guide-tokyo/)**

---

## 🤝 Remerciements

* **Fabien Simon :** Un grand merci pour ton investissement, ton accompagnement et tes précieux retours tout au long du module d'intégration D12 ! :D
