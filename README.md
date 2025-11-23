# Projet : Site de Recettes Responsif - Partie site de Recettes par :
# Canpolat Demirci-Ozmen, Lakshman Muralitharan, Luka Plouvier

# Groupe de 6 : Canpolat Demirci-Ozmen, Lakshman Muralitharan, Luka Plouvier, Maxime ELIOTT, Rayan BISSON, Jimmy-COLOMB-RAVAT

Nous avons commencé par définir les objectifs de notre projet : créer un site de recettes clair, moderne et adapté à tous les supports. Pour cela, nous avons d’abord listé les éléments essentiels à afficher comme l’image du plat, les ingrédients, les étapes, ainsi que les notes et avis des utilisateurs. Ensuite, nous avons esquissé plusieurs maquettes à la main afin de réfléchir à l’agencement global, puis nous les avons reproduites sur Figma pour avoir un rendu plus professionnel.

En parallèle, une partie du groupe a commencé à coder la structure HTML de base afin de gagner du temps et de préparer l’intégration. Après plusieurs échanges, nous avons validé une charte graphique simple et lisible, avec des icônes visuelles (étoiles, horloge, etc.) pour améliorer l’expérience utilisateur. Nous avons également pensé la responsivité du site pour qu’il s’adapte automatiquement aux différents écrans (ordinateur, tablette, mobile).

Enfin, nous avons harmonisé l’ensemble avec un header et un footer cohérents, inspirés de ceux du site de recettes, en supprimant les redirections inutiles pour ne garder que l’essentiel : contact, mentions légales, réseaux sociaux et newsletter.

En résumé : 

## 🎯 Objectif du Projet
L’objectif de ce projet est de concevoir un **site web de recettes** moderne, intuitif et responsive.  
Il permet aux utilisateurs de :

- Visualiser les ingrédients et les étapes de préparation,
- Voir les avis,
- Consulter les recettes populaires et récentes.

Le projet inclut également une mise en avant du design (UI/UX) via des **maquettes** et un code pensé pour être **responsive** (adapté aux ordinateurs, tablettes et mobiles).

---

## 🖼️ Maquettes
Nous avons réalisé plusieurs maquettes afin de prévoir l’affichage sur différents supports (desktop et mobile). Ca a été l'objet de nombreux débats.
On a débatu sur les couleurs et l'agencement et la taille des éléments. Au fur et à mesure des esssais utilisateur par Jimmy, nous avons amélioré l'interface.

### Page d’accueil / Liste de recettes
- Affichage des recettes sous forme de cartes avec **image du plat**, **titre**, **temps de préparation** et **note moyenne**.
- Présentation claire et répétée pour permettre un **parcours utilisateur rapide**.

### Page détaillée d’une recette
- **Photo ou vidéo du plat** en haut de la page.
- **Liste des ingrédients** (lisible et organisée).
- **Étapes de préparation** numérotées.
- Section **avis et notes des utilisateurs** pour favoriser l’interaction.
- Mise en avant du **temps de préparation** avec un pictogramme (horloge).

### Responsive Design (Mobile)
- Navigation simplifiée avec un **menu burger**.
- Cartes des recettes adaptées à la largeur de l’écran.
- Organisation en colonnes pour une lecture fluide.
- Footer conservé avec accès aux réseaux sociaux et à la newsletter.

Ces choix garantissent une expérience utilisateur homogène sur tous les supports.

---

## 💻 Choix Techniques & Code
- **HTML5 / CSS3 / JavaScript** pour la base du projet.
- **Flexbox et Grid CSS** pour organiser les sections et assurer la responsivité.
- **Icônes (horloge, étoiles)** pour une interface plus visuelle et intuitive.
- **Footer** commun à toutes les pages avec :
  - Liens de contact,
  - Mentions légales,
  - Inscription à la newsletter,
  - Réseaux sociaux (Instagram, Facebook, YouTube, TikTok).

### Principes de développement
1. **Responsivité** :  
   - Utilisation de media queries pour adapter l’affichage.  
   - Menu burger sur mobile.  
   - Réduction/adaptation des images.  

2. **Accessibilité** :  
   - Texte contrasté, lisible.  
   - Structure HTML sémantique.  

3. **Réutilisabilité** :  
   - Composants modulaires (cartes recettes réutilisables, header et footer repris d'anciennes SAés).  
