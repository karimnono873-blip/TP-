# 🐸 Simulateur Interactif Saute-Mouton - TP POO

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-Algorithms-007396?style=for-the-badge&logo=java&logoColor=white)
![USTHB](https://img.shields.io/badge/USTHB-FGE-9334e6?style=for-the-badge)

Ce dépôt contient le projet complet (Code source Java et Interface Web Interactive) pour le **TP N°3 : Programmation des systèmes par les méthodes de POO**. 

L'application modélise et résout le problème algorithmique du jeu "Saute-Mouton", en intégrant le code source de l'algorithme ainsi qu'une interface graphique moderne (thème Material/Google Pixel) dotée d'un moteur d'exécution en temps réel.

---

## 🎓 Contexte Académique
* **Université :** Université des Sciences et de la Technologie HOUARI BOUMEDIENE - USTHB
* **Faculté :** Faculté de Génie Electrique FGE - Département d'Automatique
* **Module :** TP POO
* **Niveau & Spécialité :** Master 1 AII (Automatique)
* **Enseignant :** M. MENANI

---

## 🎯 Règles du Système Modélisé
Le système est basé sur un plateau unidimensionnel avec des règles de transition strictes :
* **Configuration de départ :** Le plateau est initialisé avec les pièces noires à l'extrémité gauche et les rouges à droite. Un unique espace vide les sépare au centre. La symétrie est respectée (autant de pièces de chaque côté).
* **Objectif final :** Inverser totalement le plateau pour ramener l'intégralité des pièces rouges à gauche et les noires à droite, avec l'espace vide de retour au centre.
* **Mécanismes de déplacement :**
  * Vecteurs directionnels : Avancée vers la droite pour les noirs, vers la gauche pour les rouges.
  * Déplacement simple : Possible uniquement vers la case adjacente si celle-ci est libre.
  * Saut : Autorisé par-dessus un unique obstacle de la faction adverse, à condition que la case de réception soit libre.
* **Critères d'arrêt :** Le programme s'interrompt sur un succès (objectif atteint) ou sur une situation de blocage (plus aucun mouvement matériel n'est valide pour aucun pion).

---

## ✨ Fonctionnalités Principales
* **Moteur Logique Strict :** L'algorithme valide rigoureusement chaque intention de mouvement selon l'arbre de décision.
* **Détection de Deadlock :** Scan complet du tableau à chaque itération pour identifier les états de blocage irrémédiables.
* **Architecture Web Monolithique :** Un fichier HTML/CSS/JS unique regroupant la théorie, le code Java formaté, et le simulateur interactif.
* **Design "Google Pixel" :** Interface utilisateur soignée avec une palette de couleurs (Bleu, Cyan, Violet), ombres dynamiques et typographies claires.
* **Console d'Exécution Temps Réel :** Panneau de débogage affichant l'historique des actions, les logs du système, et les alertes de violation de règles en direct.

---

## 🚀 Déploiement et Utilisation
Cette version est prête à être déployée (par exemple via GitHub Pages) et ne nécessite aucune compilation en ligne de commande pour visualiser le comportement logique :
1. Récupérez le fichier `index.html`.
2. Lancez-le dans n'importe quel navigateur web standard (Chrome, Edge, Firefox, Safari).
3. Utilisez l'interface pour tester le système : paramétrez la taille (N jusqu'à 10) et manipulez les éléments pour simuler la mémoire.

---

## 👨‍💻 Auteur
**Dahane Ahmed Lamine** *Spécialité Automatique et Informatique Industrielle - Développement d'Interfaces et Systèmes*
