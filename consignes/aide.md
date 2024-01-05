
### AIDE
## Déclaration des variables : 
 const/let/var pour déclaration des variables => plus de var. ON déclare tout en const et si le contenu d'une variable doit être modifié, on la déclare en let

pas de déclaration de type en javascript (comme ne PHP / pas comme en c#)
 Pour voir le type d'un élément : typeof

## console.
console.log() pour afficher objet ou variable dans la console (F12 sous navigateur/ console)

console.dir() pour afficher les détails de l'objet 

## Principe javascript : récupérer un élément du DOM qui a été créé par le navigateur puis modifier ses propriétés

document.querySelector() pour récupérer un objet du DOM (aussi bien des objets html, que des class ou des id)
Exemple 1 :
si dans mon HTML j’ai cet objet :
 <p class="trucBidule">BlablaBla...</p>

en js, je pourrais récupérer cet objet comme cela : 
const monObjet = document.querySelector(".trucBidule") ;

Exemple 2 :
si dans mon HTML j’ai cet objet :
 <p id="trucBidule">BlablaBla...</p>

en js, je pourrais récupérer cet objet comme cela : 
const monObjet = document.querySelector("#trucBidule") ;

Exemple 3 :
si dans mon HTML j’ai cet objet :
 <p id="trucBidule">BlablaBla...</p>

en js, je pourrais récupérer cet objet comme cela : 
const monObjet = document.querySelector("p") ;

## modifier textContent d'un objet
C’est la propriété textContent de l’objet qui contient le texte affiché.
nomOBjet.textContent = "blablabla..." ; 

## modifier la couleur d'un objet
C’est la propriété style.color de l’objet qui contient le texte affiché.
nomOBjet.style.color = "nomDeLaCouleur"; 

## ajouter un écouteur à un objet
en 3 étapes :
1 => récupérer le formulaire => const leFormulaire = document.querySelector("form") ;//
2 => écrire la procédure qui devra être appelée sur le bouton => 
function verifEtCalcul(e){
    e.preventDefault();
    ...
}
3 => ajouter l'écouteur au bouton et indiquer quelle procédure appeler
form.addEventListener("submit",verifEtCalcul) 

remarque : l'instruction e.preventDefault(); permet d'annuler l'envoie du formulaire au serveur Web 

.value pour récupérer contenu de l'élément

.toFixed(1) pour arrondir à 1 chiffre après la virgule



document.querySelectorAll("input") // faire un console.log pour voir les "noeuds" node (on récupère une liste)





