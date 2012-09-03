# Convention d'écriture

La communauté PHP est large et diversifiée, composée d'inombrables bibliothèques, frameworks et composants. Il est 
commode pour les développeurs PHP d'en choisir plusieurs et de les combiner au sein d'un même projet. Il est toute fois 
important que le code PHP suive (autant que possible) des conventions d'écritures communes facilitant aux développeurs 
le mélange et l'accord des bibliothèques dans les projets.

Le [Framework Interop Group][fig] (communément appelé le "Groupe des Standards PHP") a proposé et validé une série de 
recommandations d'écriture, appelées [PSR-0][psr0], [PSR-1][psr1] et [PSR-2][psr2]. Ne laissez pas ces noms bisares 
vous dérouter, ces recommendations sont simplement un ensemble de règles que des projets tels que Drupal, Zend, CakePHP,
 phpBB, AWS SDK, FuelPHP, Lithium... commencent à adopter. Vous pouvez commencer à les utiliser pour vos projets 
 personnels ou continuer à utiliser vos propres conventions.

Idéalement, vous pouvez écrire du code PHP qui respecte une ou plusieurs de ces normes, pour que les autres développeurs
puissent facilement lire et travailler avec votre code. Elles font toutes références à la recommandation précédente, 
c'est à dire que l'utilisation de PSR-1 nécessite PSR-0 mais pas PSR-2. 

* [Plus de détail sur PSR-0][psr0]
* [Plus de détail sur PSR-1][psr1]
* [Plus de détail sur PSR-2][psr2]

Vous pouvez utiliser les règles [phpcs-psr][phpcs-psr] pour [PHP_CodeSniffer][phpcs] afin de vérifier le bon respect de 
ces recommandations. Utilisez [le correcteur de standard PHP][phpcsfixer] de Fabien Potencier pour modifier 
automatiquement la syntaxe de votre code pour qu'il devienne respectueux de ces standards, vous évitant de corriger ces 
écarts manuellement.

[fig]: http://www.php-fig.org/
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[phpcs]: http://pear.php.net/package/PHP_CodeSniffer/
[phpcs-psr]: https://github.com/klaussilveira/phpcs-psr
[phpcsfixer]: http://cs.sensiolabs.org/
