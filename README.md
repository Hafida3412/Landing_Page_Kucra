<h3 align="center">Landing Page KUCRA</h3>

<p align="left">Utilisation des langages HTML et CSS</p>
<br>

**Effets CSS utilisés:**

__- Effet Parallax:<br>__
  Utilisation de background-attachment: fixed; dans la section #parallax.<br>
  Cela crée un effet où l'image de fond défile à un rythme différent par rapport au contenu, donnant une impression de profondeur.<br>
<img width="952" alt="image" src="https://github.com/user-attachments/assets/9157614a-7630-44d5-8bf3-9697bb2256a7"><br>

  
__- Hover:<br>__
La plupart des cartes et images ont des effets hover. <br>
  Par exemple, les cartes dans le contenu principal se déplacent légèrement vers le haut grâce à transform: translateY(-15px);. <br>
  Cela attire l'attention des utilisateurs lorsqu'ils passent la souris dessus.<br>
Les images de membres d’équipe passent de noir et blanc à couleur lorsqu’elles sont survolées (filter: grayscale(1); pour le noir et blanc<br>
  et filter: grayscale(0); pour la couleur), ce qui attire l’attention sur ces membres.<br>

  <img width="916" alt="image" src="https://github.com/user-attachments/assets/98aa8e38-af3e-4ecf-834e-132643659c5c"><br>

__- Flexbox:<br>__
Utilisé dans plusieurs parties de la mise en page (ex. : la navigation, les cartes) pour créer des mises en page réactives et flexibles.<br>
Par exemple, display: flex; sur le #container aligne facilement les cartes côte à côte dans un espace donné.<br>

__- Blur:<br>__
Les images de la section "What your client says" ont un flou par défaut (filter: blur(5px);) qui disparaît lorsqu’elles sont survolées.<br>
  Cela attire le regard et ajoute un effet visuel interactif.<br>

<img width="944" alt="image" src="https://github.com/user-attachments/assets/1153b465-796a-40e9-98b7-a5554b540d10">
