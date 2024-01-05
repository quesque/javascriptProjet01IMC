# Coder un calculateur d'IMC

> ctrl+shift+v sur VS Code pour analyser ce fichier markdown

<br>

Le but de ce projet est de coder un **calculateur d'IMC** à partir des valeurs rentrées par un utilisateur dans les **deux inputs**.

formule de calcul de l'imc : poids en kg*10000 / (taille en cm * taille en cm)
<br>


### Fonctionnalités JavaScript à coder pour ce projet

1. Gérez les inputs, retrouvez leur valeur dans votre script quand on clique sur le bouton.
2. Faites une validation basique, empêchez le calcul si l'utilisateur laisse un ou deux inputs vides. <br>
Montrez également un message pour l'informer de l'erreur (ex : "Veuillez remplir les inputs").
1. Calculez l'IMC avec les valeurs rentrées.
2. Calculez le rang de l'IMC par rapport à "BMIData"
const BMIData = [
  { name: "Maigreur", color: "midnightblue", range: [0, 18.5] },
  { name: "Bonne santé", color: "green", range: [18.5, 25] },
  { name: "Surpoids", color: "lightcoral", range: [25, 30] },
  { name: "Obésité modérée", color: "orange", range: [30, 35] },
  { name: "Obésité sévère", color: "crimson", range: [35, 40] },
  { name: "Obésité morbide", color: "purple", range: 40 },
];
3. Remplissez l'interface en fonction des résultats
   
<br>




### AIDE
voir const/let/var pour déclaration des variables => plus de var. ON déclare tout en const et si le contenu d'une variable doit être modifié, on la déclare en let
console.log() pour afficher objet ou variable dans la console (F12 sous navigateur/ console)
console.dir() pour afficher les détails de l'objet 
document.querySelector() pour récupérer un objet du DOM
form.addEventListener() pour ajouter un "écouteur d'événement" sur la feuille 2 paramètres : le nom de l'événement à écouter, ici "submit", puis le nom de la méthode appelée par cet événement
e.preventDefault() 
document.querySelectorAll("input") // faire un console.log pour voir les "noeuds" node (on récupère une liste)
.Value pour récupérer contenu de l'élément
truthy
falsy 0 null undefined false ""

