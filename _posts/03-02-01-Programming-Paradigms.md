---
isChild: true
---

## Paradigmes de programmation

PHP est un langage souple et dynamique permettant des techniques de programmation variées. Il a évolué énormément ces 
dernières années, principalement par l'ajout d'un solide modèle orienté objet depuis PHP 5.0 (2004), les fonctions
anonymes et les espaces de noms depuis PHP 5.3 (2009) et les "traits" depuis PHP 5.4 (2012).

### Programmation orientée objet

PHP possède un panel de fonctionnalités orientées objet comprenant le support des classes, classes abstraites, 
interfaces, héritage, constructeurs, clonage, exceptions et bien plus encore.

* [Plus de détails sur la programmation orintée objet PHP][oop]
* [Plus de détails sur les "traits"][traits]

### Programmation fonctionnelle

PHP supporte les fonctions de première classe, ce qui signifie qu'une fonction peut être assignée à une variable. Les 
fonctions définies par l'utilisateur ainsi que celles pré-définies peuvent être assignées à des variables. Les fonctions
peuvent être passées en argument et invoquées dynamiquement. Les fonctions peuvent être passées comme argument à 
d'autres fonctions (cette fonctionnalité est appellée fonction d'ordre supérieur) et elles peuvent renvoyer d'autres 
fonctions.

La récursivité est une fonctionnalité qui permet à une fonction de s'appelée soit même est également supportée par le 
langage mais la majeure partie du code source en PHP utilise l'itération.

Les fonctions anonymes (incluant le support des "closures") est disponible depuis PHP 5.3 (2009).

PHP 5.4 a ajouté la possibilité d'utiliser les "closures" dans la portée d'un objet et a amélioré le support des 
fonctions de rappels de telle sorte qu'ils peuvent être échangés avec des fonctions anonymes dans la majorité des cas.

* Poursuivre la lecture sur [la programmation fonctionelle en PHP](/pages/Functional-Programming.html)
* [Plus de détails sur les fonctions anonymes][anonymous-functions]
* [Plus de détails sur les classes closures][closure-class]
* [Plus de détails sur les RFC des closures][closures-rfc]
* [Plus de détails sur les fonctions de rappels][callables]
* [Plus de détails sur l'appel dynamique des fonctions avec `call_user_func_array`][call-user-func-array]

### Métaprogrammation

PHP supporte diverses formes de métaprogrammation à travers des mécanismes tels que la réflexion et les méthodes 
magiques. Il y a beaucoup de méthodes magiques disponibles comme : `__get()`, `__set()`, `__clone()`, `__toString()`, 
`__invoke()`... qui permettent aux développeurs de modifier le comportement d'une classe. Les développeurs Ruby 
reprochent souvent à PHP de ne pas avoir d'équivalent de leur `method_missing` mais on le trouve sous deux méthodes : 
`__call()` et `__callStatic()`.

* [Plus de détails sur les méthodes magiques][magic-methods]
* [Plus de détails sur la réflexion][reflection]

[oop]: http://www.php.net/manual/fr/language.oop5.php
[anonymous-functions]: http://www.php.net/manual/fr/functions.anonymous.php
[closure-class]: http://php.net/manual/fr/class.closure.php
[callables]: http://php.net/manual/fr/language.types.callable.php
[magic-methods]: http://php.net/manual/fr/language.oop5.magic.php
[reflection]: http://www.php.net/manual/fr/intro.reflection.php
[traits]: http://www.php.net/traits
[call-user-func-array]: http://php.net/manual/fr/function.call-user-func-array.php
[closures-rfc]: https://wiki.php.net/rfc/closures
