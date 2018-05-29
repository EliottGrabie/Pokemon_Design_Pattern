# Pokemon_Design_Pattern

Diagramme de classe :

Quel sont les problèmes engendrés par l’implémentation du code de chaque attaque dans la classe ?

  -Dupplication de code ne cas de même attaque entre des pokemons différents
    => solution : utiliser un design pattern strategy 
    

Pattern de strategy :

Quel sont les problèmes engendrés par cette solution ?
  -Dupplication de code dans le cas d'un ajout de type d'énergie, que ce soit en classe ou pour l'ajout du type dans l'énergie multicolore
    =>solution : utiliser un pattern Decorator
  

Pattern Decorator :

L’agrégation entre les classes Pokemon et Energie a-t-elle une incidence ?


Fusion Startegy / Decorator :



