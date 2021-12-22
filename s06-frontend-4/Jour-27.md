# Objectifs journaliers

## Mercredi 22/12/2021


### Javascript :

#### Découvrir le `DOM` :

* [X] Savoir modifier un document (https://javascript.info/modifying-document)
  * Savoir :
    * [X] Créer un `element`
    * [X] Utilier les différentes méthodes d'insertions
    * [X] Supprimer un `node` Note : .remove(), .clear() pour     tout supprimer
    * [X] Cloner un `node` Note : L’appel elem.cloneNode(true) crée un clone “profond” de l’élément – avec tous les attributs et sous-éléments. Si nous appelons `elem.cloneNode(false`), alors le clone est fait sans éléments enfants.

* [X] Savoir modifier un style dans un document (https://javascript.info/styles-and-classes)
  * [X] Comprendre la différence entre `className` et `classList`
    Note : classListe retourne une liste de classe, il existe 
    des méthodes pour travailler dessus
  * [X] Savoir ajouter, supprimer et toggle une classe
  * [X] Savoir manipuler les styles dans les `elements`

* [ ] Comprendre la tailles des fenêtres et le défilement (https://fr.javascript.info/size-and-scroll-window)
  * [X] Comprendre la différence entre la taille de la fenêtre et du document
  Note : `documentElement.clientWidth` sans la barre de scroll
  Note : `documentElement.clientheight ` sans la barre de scroll
  Note : `window.innerWidth` pleine largeur de la fenêtre
  Note : `window.innerHeight` pleine hauteur de la fenêtre
  * [ ] Comprendre le fonctionnement du défilement


* [ ] Comprendre le fonctionnement des coordonnées dans une page web (https://fr.javascript.info/coordinates)
  * [ ] `position:fixed`
  * [ ] `position:absolue`


* [ ] Découvrir les évènements du `DOM` (https://javascript.info/introduction-browser-events)
  * Comprendre ce que sont les : 
    * [X] évènements liés à la souris
    * [X] évènements liés aux formulaires
    * [X] évènements liés au clavier
    * [X] évènements liés au document
    * [ ] évènements liés au CSS
  * [ ] Comprendre ce qu'est un `handler` et comment cela fonctionne
  Note : Le handler est un bloc de code qui s'exécute suite à
  un événement, on appel cela un gestionnaire d'événement.
  * [X] Comprendre le fonctionnement et l'utilité de `addEventListener` et `removeEventListener`
  Note : on selectione l'élément sur le quel il y a l'écouteur
  d'événements.


* Codewars :
  * [ ] Count of positives / sum of negatives (https://www.codewars.com/kata/576bb71bbbcf0951d5000044)
  * [ ] Odd or Even? (https://www.codewars.com/kata/5949481f86420f59480000e7)


