![Logo de la compagnie ohmyfood.](/footage/Logo/ohmyfood-white.png)

__Ma mission est de développer un site “mobile first” qui répertorie les menus de restaurants gastronomiques__, en m'appuyant sur [les maquettes Figma](https://www.figma.com/file/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=0-1&t=Rhtl9kN6JZFVsG32-0)
fournies par notre UX designer.

- Utilisation du préproceseur SASS, avec fichiers SCSS
- Nommage de classes avec la convention BEM
- Organisation des dossiers avec le pattern 7-1
- Utilisation d'auto-prefixer

Voici ce qui m'a été demandé:

 - Mobile first
 - site responsive
 - Version desktop
 - utilisation de Sass
 
- __Page d’accueil (x1)__
  - Affichage de la localisation des restaurants.
  - Une courte présentation de l’entreprise.
  - Une section contenant les 4 menus sous forme de cartes. Au clic sur la carte,
l’utilisateur est redirigé vers la page du menu.

- __Pages de menu (x4)__
  - 4 pages contenant chacune le menu d’un restaurant.
  
- __Footer__
  - Le footer est identique sur toutes les pages.
  - Au clic sur "Contact", un renvoi vers une adresse mail est effectué.

- __Header__
  - Le header est présent sur toutes les pages.
  - Sur la page d’accueil, il contient le logo du site.
  - Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.
  
- __Animations__
  - _Boutons_
    - Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
      L’ombre portée devra également être plus visible.
    - À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
      bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
      remplir progressivement. Pour cette première version, l’effet peut apparaître au
      survol sur desktop au lieu du clic.
  - _Page d’accueil_
    - Quand l’application aura plus de menus, un “loader” sera nécessaire. Sur cette
      maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3
      secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
      utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
      toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
      graphique du site.
  - _Pages de menu_
    - À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
      décalage dans le temps. Ils pourront apparaître soit un par un, soit par groupe
      “Entrée”, “Plat” et “Dessert”.
    - Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
      Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
      la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
      sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
      des points de suspension.
