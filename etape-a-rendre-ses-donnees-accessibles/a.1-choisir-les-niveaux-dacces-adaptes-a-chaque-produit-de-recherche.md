# 1. Choisir les niveaux d'accès adaptés à chaque produit de recherche

Pour être FAIR, les métadonnées doivent rester accessibles même si les données ne le sont plus. Avec le temps, les données peuvent disparaître. Les métadonnées peuvent être très utiles dans ce cas, car elles permettront d'avoir de précieuses informations sur le jeu de données disparu et de laisser la possibilité à d'autres chercheurs de reprendre et poursuivre les recherches associées. L'entrepôt a un rôle majeur dans ce cas, étant donné que c'est lui qui héberge les données et métadonnées associées.

## **Garder des informations sur les données si elles sont inaccessibles**

Maintenir des jeux de données en ligne a un coût. Avec le temps, il y a des risques de dégradation. Dans ce cas, les jeux de données peuvent ne plus être disponibles. De même, des restrictions d'accès peuvent exister.

Si les données disparaissent ou sont inaccessibles, les métadonnées continueront à fournir de précieuses informations pour que d'autres chercheurs puissent connaître l'existence des données, contacter les personnes ressources ou encore retrouver les articles associés aux données.

## **Choisir un niveau d'authentification**

Pour être FAIR, les données sensibles doivent pouvoir être accessibles par authentification. Les protocoles de communication HTTPS et FTPS peuvent demander un certificat d'identification aux personnes voulant accéder au site. L'entrepôt sur lequel les données sont déposées doit ainsi pouvoir identifier les visiteurs et donner des droits spécifiques pour donner accès ou non aux données sensibles.

Bien que produites sur fonds publics, certaines données ne peuvent pas être accessibles publiquement pour des raisons légitimes. Ce sont par exemple :

* des données à caractère personnel (données permettant d'identifier une personne, directement ou indirectement) ;
* des données relevant de la sécurité nationale ;
* des données sujettes à un dépôt de brevet.

{% hint style="info" %}
**ll est conseillé d'avoir recours au cryptage de vos données sensibles pour éviter des intrusions malveillantes.**
{% endhint %}

Si vos données doivent rester privées, spécifiez les conditions exactes dans lesquelles elles peuvent être accessibles : qui a le droit d'y accéder et comment.

{% hint style="info" %}
Le choix de l'entrepôt de données peut donc dépendre du protocole de communication qu'il utilise.
{% endhint %}
