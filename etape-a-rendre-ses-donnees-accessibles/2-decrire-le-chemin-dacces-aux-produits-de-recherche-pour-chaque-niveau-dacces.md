# 2. Décrire le chemin d'accès aux produits de recherche pour chaque niveau d'accès

{% hint style="info" %}
L'accessibilité à vos données doit être mentionné dans la documentation ou les métadonnées. S'il existe des contraintes liées au type de données (sensibles, confidentielles), elles doivent figurer dans le PGD.&#x20;
{% endhint %}

## Stockage et sauvegarde pendant le processus de recherche&#x20;

La gestion des données de recherche du projet doit être réfléchie et organisée différemment en fonction de l'étape à laquelle on se situe, pendant et après le projet.

La première étape concerne le **stockage sécurisé** et la **sauvegarde** des données durant toute la durée du projet. Les objectifs sont de :

* garantir la sécurité des données,
* faciliter l'accès pour l'ensemble des collaborateurs du projet.

Il est très important de prévenir la perte et la dégradation des données pendant le projet du fait :

* du matériel
* du logiciel utilisé
* du format de fichier
* de la perte de la signification du contenu
* d'un mauvais étiquetage
* d'un manque de rigueur dans le nom des fichiers. &#x20;

Source : Marie-Claude Quidoz - [Atelier « Carnets de terrain électroniques »](http://rbdd.cnrs.fr/IMG/pdf/quidoz\_atelier2018.pdf?480/cd645e6864223eaae2a37ea4d2b45077f07b61d1), Montpellier, 28-29/03/2018

### Mesures de sauvegarde à mettre en place

Une sauvegarde efficace signifie qu'il faut **dupliquer et stocker** les données à différents endroits sur différents supports selon une temporalité pertinente pour le projet.&#x20;

L'idéal est d'appliquer la **règle du 3-2-1**, ce qui veut dire :

* garder 3 exemplaires des données,
* sur 2 supports ou technologies différents,&#x20;
* dont 1 se trouve hors site.

Dans tous les cas, il faut organiser et planifier ces sauvegardes en veillant à bien gérer les versions. A chaque point d'étape du projet, sélectionner les données à sauvegarder, à supprimer. Les différents états des données sont conservés en corrélation avec les différentes étapes de traitement, ce qui permet de revenir à une version antérieure si besoin.\
\
Cela nécessite aussi de définir un hébergement et une politique de sauvegarde adaptés aux besoins du projet concernant les spécificités de stockage des données (par exemple en cas de données sensibles, de grosse volumétrie...). Cela peut être sur des serveurs locaux (machines virtuelles), un cloud institutionnel avec accès sécurisé...

Il est recommandé d'éviter au maximum les outils du type One Drive, Google Drive, Dropbox, etc.

{% hint style="info" %}
**Dans tous les cas, ne pas hésiter à se rapprocher de son établissement afin de connaitre les espaces de stockage sécurisés mis à disposition.**
{% endhint %}

## **Utiliser un protocole libre et ouvert**



Pour être FAIR, les données doivent pouvoir être récupérables via un protocole de communication standardisé. Il existe plusieurs protocoles qui sont destinés à des types de communications particuliers. Le HTTP et le FTP sont des protocoles standards servant respectivement à distribuer des pages Web et à transférer des fichiers. L'entrepôt sur lequel vos données sont déposées devrait utiliser des protocoles standards tels que le HTTP et le FTP.

Les protocoles de communication libres et ouverts sont librement utilisables et interopérables. Ils peuvent fonctionner avec plusieurs logiciels, contrairement aux protocoles propriétaires. Ils facilitent ainsi le libre accès aux données. Leur documentation technique étant accessible publiquement, les nouveaux outils qui verront le jour pourront s'appliquer avec ces protocoles.

{% tabs %}
{% tab title="Protocole à utiliser" %}
De nombreux protocoles standards sont libres et ouverts. Ex : HTTP, FTP, SMTP (Simple Mail Transfer Protocol)...
{% endtab %}

{% tab title="Protocole à éviter" %}
Les protocoles propriétaires ou dont la documentation n'est pas accessible publiquement. Ex : Protocole Skype, Microsoft, Exchange Server…
{% endtab %}
{% endtabs %}

##

Crédits : Inist-CNRS - [PARCOURS INTERACTIF SUR LA GESTION DES DONNÉES DE LA RECHERCHE](https://doranum.fr/enjeux-benefices/parcours-interactif-sur-la-gestion-des-donnees-de-la-recherche/)
