---
isChild: true
---

## Installation sous Windows

PHP est disponible de plusieurs façons sous Windows. Vous pouvez [télécharger les fichiers binaires][php-downloads] et 
depuis peu, utiliser une installation automatisée avec un '.msi'. L'installeur n'est plus supporté depuis PHP 5.3.0.

Pour apprendre et développer sur un serveur local, vous pouvez utiliser le serveur web intégré avec PHP 5.4 sans vous 
préoccupez de sa configuration. Si vous voulez un "tout en un" contenant un serveur web complet et MySQL alors des 
outils tels que [Web Platform Installer][wpi], [Zend Server CE][zsce], [XAMPP][xampp] et [WAMP][wamp] vous aideront à 
mette en place rapidement un environnement de développement sous Windows. Cependant, ces outils peuvent être légèrement 
différents en production donc soyez atentifs aux différences des environnements si vous développez sous Windows et 
déployez sous Linux.

Si vous devez mettre en production sur une plate-forme Windows alors IIS7 vous assurera la meileure stabilité et 
performance. Vous pouvez utiliser [phpmanager][phpmanager] (un grefon d'interface graphique pour IIS7) pour faciliter 
la configuration et la gestion de PHP. IIS7 intègre un FastCGI prêt à l'emploi, vous devez juste configurer PHP comme 
gestionnaire. Vous trouverez de l'assistance et des ressources complémentaires sur la zone dédiée à PHP sur 
[iis.net][php-iis].

Généralement, exécuter votre application dans différents environnements en développement et en production peut produire
des bogues étranges. Si vous développez sous Windows et déployez sur Linux (ou tout autre système que Windows) alors
vous pouvez envisager d'utiliser des machines virtuelles. Celà peut paraître bisare mais grâce à [Vagrant][vagrant] vous
pouvez installer de simples conteneurs, puis à l'aide de [Puppet][puppet] ou [Chef][chef], vous pouvez nourrir ces 
boîtes et les partager avec vos collègues pour être sur que vous travaillez tous sur la même plate-forme. 
Plus de détails à ce sujet prochainement.

[php-downloads]: http://windows.php.net
[phpmanager]: http://phpmanager.codeplex.com/
[wpi]: http://www.microsoft.com/web/downloads/platform.aspx
[zsce]: http://www.zend.com/fr/products/server-ce/
[xampp]: http://www.apachefriends.org/fr/xampp.html
[wamp]: http://www.wampserver.com/
[php-iis]: http://php.iis.net/
[vagrant]: http://vagrantup.com/
[puppet]: http://www.puppetlabs.com/
[chef]: http://www.opscode.com/
