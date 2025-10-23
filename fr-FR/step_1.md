Le conteneur Query Height (cqh) est une unité qui spécifie une taille relative aux dimensions de l'élément conteneur d'un élément.

`1cqh` représente 1 % de la hauteur du conteneur. Par exemple, si la hauteur du conteneur est de 300px, alors une valeur de `10cqh` sur une propriété sera de 30px.

L’un des avantages de l’utilisation des unités `cqh` plutôt que `px` (unités de pixels) pour dimensionner les éléments est que les éléments seront redimensionnés avec leur conteneur. Cela se produit généralement lorsque tu redimensionnes une fenêtre de navigateur ou affiches une page web sur un autre écran.

Voici un exemple :

![Un gif montrant les tailles de police changeant lorsque le navigateur modifie la hauteur et la largeur](images/cqh_cqw.gif)

Dans l'exemple, la taille de la police du texte de l'histoire principale a été définie pour utiliser `cqh`, elle change donc avec la hauteur du navigateur.

La taille de la police du texte dans la barre de navigation a été définie pour utiliser `cqw`, elle change donc avec la largeur du navigateur.
