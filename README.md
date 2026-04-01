# 🚀 AD ASTRA — Jeu de Voyage Interstellaire

## 📝 Description

**AD ASTRA** est un jeu vidéo 2D développé en Python avec la bibliothèque Pygame.
Le joueur incarne un vaisseau spatial traversant un tunnel interstellaire en évitant des obstacles, en détruisant des astéroïdes et en survivant le plus longtemps possible.

Le jeu propose une expérience dynamique mêlant :

* déplacement en pseudo-3D dans un tunnel
* gestion de vitesse
* tirs et destruction d’obstacles
* système de bonus et de bouclier
* score évolutif avec sauvegarde du high score

---

## 🎮 Gameplay

### Objectif

Survivre le plus longtemps possible en :

* évitant les collisions
* restant à l’intérieur du tunnel
* détruisant les obstacles

### Mécaniques principales

* 🚀 **Déplacement libre** du vaisseau (haut, bas, gauche, droite)
* 🔫 **Tirs laser** pour détruire les astéroïdes
* 🛡️ **Bouclier** temporaire avec jauge d’énergie
* 💥 **Système de collision** avec dégâts variables
* ❤️ **Bonus de vie**
* ⚡ **Gestion de vitesse dynamique**
* 🌀 **Tunnel évolutif** (taille et trajectoire changeantes)

---

## ⌨️ Contrôles

| Touche       | Action                           |
| ------------ | -------------------------------- |
| ⬅️➡️⬆️⬇️     | Déplacement                      |
| W            | Tir                              |
| X            | Activer / désactiver le bouclier |
| Shift droit  | Accélérer                        |
| Shift gauche | Ralentir                         |
| Entrée       | Quitter après Game Over          |

---

## 🧠 Fonctionnalités techniques

* 🎨 Rendu graphique avec effet de profondeur (pseudo 3D)
* 🔄 Génération procédurale :

  * obstacles
  * bonus
  * tunnel
* 💾 Sauvegarde du **high score** dans un fichier local
* 🔊 Intégration de sons :

  * tirs
  * explosions
  * collisions
  * musique de fond
* 🧩 Architecture modulaire (gestion objets via dictionnaires)

---

## 📁 Structure du projet

```
📦 AD-ASTRA
 ┣ 📂 image/
 ┣ 📂 sounds/
 ┣ 📂 font/
 ┣ 📄 Interstellaire_ATSE_DEMBELE.py
 ┣ 📄 high_score.txt
 ┗ 📄 README.md
```

---

## ⚙️ Installation & Lancement

### Prérequis

* Python 3.x
* Bibliothèque Pygame

### Installation

```bash
pip install pygame
```

### Lancer le jeu

```bash
python AD_Astra.py
```

---

## 📊 Système de score

* Le score augmente avec le temps et la vitesse
* Un **high score** est sauvegardé automatiquement
* Affichage en temps réel :

  * score actuel
  * vies restantes
  * jauge de bouclier

---

## ⚠️ Conditions de défaite

* 💥 Collision avec des obstacles (si plus de vie)
* 🚫 Sortie du tunnel

---

## 🎓 Cadre du projet

> Ce projet a été réalisé dans un cadre strictement pédagogique (**Université Toulouse Capitole**).
>
> Les effets sonores, musiques, polices et certaines images utilisés proviennent de banques libres de droits (usage éducatif/personnel).
>
> Ils sont inclus à titre démonstratif et ne font pas l'objet d'une utilisation commerciale.

---

## ✨ Améliorations possibles

* Ajout de niveaux / progression
* Système d’ennemis intelligents
* Menu principal et interface utilisateur avancée
* Optimisation des performances
* Version multijoueur
* Portage web ou mobile

---

## 👤 Auteurs

* **Sombo Atsé**
  * 📧 sombo.atse46@gmail.com
  * https://www.linkedin.com/in/sombo-malachie-ats%C3%A9-738031276/
* **Joel-Elisée Dembele**
  * 📧 joeleliseefac@gmail.com
  * https://www.linkedin.com/in/joel-elis%C3%A9e-dembele-423a3b293/



Projet universitaire — Licence 3 MIAGE
