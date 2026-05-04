# Planificator

__Une aide pour planifier ses projets de développement avec un framework MVC__

Ce document est un aide destinée à des étudiants inscrits au bachelier en techniques graphiques de la Haute École de la Province de Liège, orientation web. Dans le cadre de leur formation, ceux-ci sont invités à prendre en main le framework [Laravel](http://www.laravel.com). Afin de les aider dans le développement de leur application, et en plus de la formation reçue sur le framework, j’ai créé une fiche type destinée à recenser tout un tas d’informations utiles pour planifier le travail.

Dans le contexte d’un développement assisté par IA, cette étape est cruciale. Les IA ne sont pas des outils magiques même s’ils peuvent parfois donner cette impression. Développer avec des IA demande de passer par des étapes de configuration précises et la rédaction de cahiers de charges fonctionnels (vision de haut niveau des objectifs de l'application), opérationnels (descriptions précise des opérations impliquées par les fonctionnalités), qualitatifs (mise en place d’outils de monitoring, tests, versionnements, intégration continue), qui requièrent une maîtrise pointue d’un vocabulaire et de concepts qui ne peut s’acquérir qu’en passant soi-même par l'écriture manuelle du code impliqué.

Si on veut coder avec des IA, il faut donc les utiliser essentiellement comme des leviers de ses propres compétences, et ces dernières doivent donc être bien présentes.

Le présent repo propose un découpage fonctionnel de l'application autour du concept de requête. Dans le Web, en tout cas, du point de vue backend, l’événement qui déclenche l’exécution du code est toujours une requête. Il est donc important de pouvoir la décrire de manière très précise et d'identifier ensuite toutes les briques qui du code qui seront impliquées dans la construction de la réponse, notamment pour pouvoir les décrire très précisément aux IA. Ce découpage peut se réaliser au travers de fiches, une par requête.

Ce qui identifie une fiche est une URL, ou plus exactement un pattern d’URL, ce qui dans Laravel s’identifie le plus communément par une route. Quand Laravel détecte une correspondance entre une URL et une route déclarée, un tas d’actions sont possibles, allant de la validation des données ou du format de l’URL à la création de vues, l’envoi d’email, l’enregistrement dans des bases de données. L’avantage d’utiliser un framework est précisément que la mise en œuvre de la plupart de ces tâches est largement aidée et prévue par le Framework. Après tout, avec l’expérience de création d’applications web qui s’accumule chez les développeurs au fur et à mesure du mûrissement de l’Internet, des patterns récurrents ont fini par apparaître et ce sont ceux-ci qu’on retrouve implémentés dans la plupart des Frameworks. 

Chaque fiche propose donc de rédiger en français les déterminants de la réponse à une requête dans les termes du Framework. Une fois ce travail de planification, accompli, il ne reste plus qu’à implémenter le code avec le Framework ou à chercher comment il prévoit de résoudre le problème posé par la requête. 

Dominique Vilain
