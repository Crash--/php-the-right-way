---
isChild: true
---

## Espaces de nom

La communauté PHP est composée d'un grand nombre de développeurs, chacun créant beaucoup de code. Ceci implique que le code d'une library PHP  est susceptible d'utiliser le même nom de classe qu'une autre library. Lorsque les deux library sont utilisées dans le même espace de nom, elles entrent en conflit et créent des problèmes.

Les _Espaces de nom_ ont été conçus pour solutionner ce problème. Comme écrit dans le manuel PHP, les espaces de nom peuvent être comparés à des répertoire d'un même système ; deux fichiers portant le même nom peuvent coexister dans deux répertoires différents. De la même façon, deux classes PHP portant le même nom peuvent coexister dans des espaces de nom différents. C'est aussi simple que cela.

Il est important que vous preniez le temps d'englober votre code dans un espace de nom afin qu'il puisse être utilisé par d'autres développeurs sans crainte de conflit avec leurs autres libraries.

L'usage recommandé des espaces de nom est décrit dans [PSR-0][psr0], qui préconise des conventions de nommage pour les fichiers, les classes et les espaces de nom.

* [En savoir plus sur les espaces de nom][namespaces]
* [En savoir plus sur PSR-0 (en)][psr0]

[namespaces]: http://php.net/manual/fr/language.namespaces.php
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
