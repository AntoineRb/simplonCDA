# Objectifs journaliers

## Mardi 21/12/2021

### Javascript

  #### Découvrir le `DOM` :
  * [X] Comprendre la différence entre `DOM`, `CSSOM` et `BOM` (https://fr.javascript.info/browser-environment) 
  Note : CSSOM est utilisé avec DOM lorsque nous modifions les règles de style du document
  
  * [X] Comprendre la différence entre les 3 types de `nodes` dans le `DOM` (https://fr.javascript.info/dom-nodes)
  Note : Un document HTML/XML est représenté dans le navigateur sous forme d’arbre DOM.
  
  * [X] Comprendre la navigation du DOM (https://fr.javascript.info/dom-navigation) :
    * [ ] Comprendre la différence entre les `Child Nodes` et les `Descendants`
      Note : Child Nodes, élément qui sont des enfants directs,
            Descendants, tout les éléments imbriqués dans un élément donné, y compris
            les enfant, leurs enfants etc...
    * [X] Comprendre la différence entre une `collection` et un `array`
    Note : les collections comme les élements du DOM sont disponnible seulement en lecture
    * [X] Comprendre la différence entre un `element` et un `node`
    Note : Un nœud est le nom générique de tout type d'objet dans la hiérarchie DOM. Un nœud peut être l'un des éléments DOM intégrés tels que document ou document. ... Un élément est un type spécifique de nœud car il existe de nombreux autres types de nœuds (nœuds de texte, nœuds de commentaire, nœuds de document, etc...
    * [ ] Bien comprendre à quoi correspond : 
      * [X] `parentElement`
      * [X] `children`
      * [X] `firstElementChild`      Note : Enfant du première element
      * [X] `lastElementChild`       Note : Enfant du dernier element
      * [X] `previousElementSibling` Note : Element voisin du précédent 
      * [X] `nextElementSibling`     Note : Element voisin du suivant 
      * [X] `parentNode`             Note : Noeud Parent
      * [X] `childNodes`             Note : Noeuds enfants
      * [X] `firstChild`             Note : 1er enfant
      * [X] `lastChild`              Note : Dernier enfant
      * [X] `previousSibling`        Note : voisin précédent
      * [X] `nextSibling`            Note : Voisin suivant
    * [ ] Faire les 3 exercices et analyser ses erreurs

* [ ] Savoir cibler dans le `DOM` (https://javascript.info/searching-elements-dom)
    * Savoir exactement ce que va cibler : 
      * [X] `querySelector`
      * [X] `querySelectorAll`
      * [X] `getElementById`
      * [X] `getElementsByName`
      * [X] `getElementsByTagName`
      * [X] `getElementsByClassName`
      * [X] `elem.matches(css)`      
         Note : retourne true (booléen) si l'élement comporte la classe CSS spécifiée, false si ce n'est pas le cas.
      * [X] `elem.closest(css)`
         Note : Recherche parmis les ancêtres de l'element si il y en un qui match
         donc qui posséde la classe css spécifié en paramètre comme attribu, une fois
         l'élément trouvé il est retourné par la méthode closest(.maClasse) par exemple.
    * [X] Comprendre la différence de sortie entre `querySelectorAll` et `getElementsBy*`

* [ ] Comprendre ce que sont que les éléments qui composent le `DOM` (https://javascript.info/basic-dom-node-properties)
  * [ ] Découvrir la différence entre les `nodeType` (1,3 et 9) [Ressource](https://developer.mozilla.org/en-US/docs/Web/API/Node/nodeType)
  * [X] Comprendre comment fonctionne `innerHTML` (quels sont les "dangers", ses limitations)
  * [X] Comprendre comment fonctionne `outerHTML` (quelle est sa particularité)
  * Comprendre comment fonctionne `nodeValue` et `data` (quelle est leur utilité)
  * [X] Comprendre comment fonctionne `textContent` (quel est son point fort)

    Note : InnerHTML est utilisé pour obtenir ou définir un contenu de la balise sélectionnée tandis que externalHTML est utilisé pour obtenir ou définir le contenu avec la balise sélectionnée.
  * [X] Comprendre comment fonctionne `hidden` 
    Note : `hidden` retourne true si l'élément est caché, false si il est visible 
    Il faut utiliser le propriété css `display` pour afficher/cacher des éléments

* [ ] Comprendre la différence entre les `properties` et les `attributes` dans le `DOM` (https://javascript.info/dom-attributes-and-properties)
  Note :  la plupart des attributs HTML standards deviennent automatiquement des propriétés des objets DOM. exemple : en html id est un attribut, en js dans le dom c'est une propriété d'un objet. Donc les attributs sont ce qui est écrit en HTML et les propriétés sont ce qui se trouve dans les objets DOM.
  * Savoir comment : 
    * [X] vérifier l'existence d'un `attribute` elem.hasAttribute(name)
    * [X] récupérer la valeur d'un `attribute`  elem.getAttribute(name)
    * [X] écrire une valeur pour un `attribute` elem.setAttribute(name)
    * [X] supprimer un `attribute`              elem.removeAttribute(name)
    * [X] récupérer une collection de tous les `attributes` elem.attributes
    Note : [Ressources](https://developer.mozilla.org/en-US/docs/Web/API/Element/attribute)


* Codewars :
  * [X] Thinkful - String Drills: Repeater (https://www.codewars.com/kata/585a1a227cb58d8d740001c3)
  * [X] Remove First and Last Character Part Two (https://www.codewars.com/kata/570597e258b58f6edc00230d)

