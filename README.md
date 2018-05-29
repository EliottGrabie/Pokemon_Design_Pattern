# Pokemon_Design_Pattern

Diagramme de classe :
 
Quel sont les problèmes engendrés par l’implémentation du code de chaque attaque dans la classe ?

  -Dupplication de code ne cas de même attaque entre des pokemons différents
    => solution : utiliser un design pattern strategy 
    

Pattern de strategy :

Quel sont les problèmes engendrés par cette solution ?
  -Dupplication de code dans le cas d'un ajout de type d'énergie ou de l'association d'énergies
    =>solution : utiliser un pattern Decorator
  

Pattern Decorator :

L’agrégation entre les classes Pokemon et Energie a-t-elle une incidence ?
  -Si un objet pokemon est détruit, les energies liés ne le sont pas 



