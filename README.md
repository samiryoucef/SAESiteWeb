
<div style="display: flex; justify-content: space-between; align-items: center;">
  <strong><em>Sup-Galilée</em></strong>
  <img src="Sup-Galilee.png" alt="Logo Université" style="height: 50px; object-fit: contain;">
</div>


------
<center> <span style="font-size: 22px;"> <b> Développement d’une application web dynamique avec gestion de base de données</b> </span> </center>

----

###### Personnes à contacter

- Nathalie Pernelle <nathalie.pernelle@univ-paris13.fr>
- Manel Zarrouk <zarrouk@lipn.univ-paris13.fr>
- Samir Youcef <youcef@lipn.univ-paris13.fr>
#### Objectif

L’objectif de cette SAE est de concevoir et développer une **application web interactive** qui exploite une base de données relationnelle.  L'architecture de l'application est illustré dans la figure suivante.  Son développement s'appuie sur les technologies suivante. 

- **JavaScript** pour dynamiser l’interface utilisateur (formulaires, validation, interactions) ;
- **PHP** pour assurer la logique métier côté serveur et l’accès à la base de données avec PDO (_Php Data Objects_)
- **Bootstrap** (ou tout autre framework CSS) pour améliorer l’ergonomie et le design de l’interface ;
- **Git** pour le versionnage du code et le suivi de l’évolution du projet.

<p align="center">
  <img src="Pasted image 20251217001719.png" alt="description">
  <br/>
  <small>Architecture de l'application à concevoir</small><br>
</p>


#### Compétences travaillées

À l’issue de cette SAE, vous serez capable de :
- Concevoir un **schéma relationnel complet** (1–1, 1–N, N–N). 
- Interroger une base de données avec **PHP (PHP Data Objects**)
- Documenter un projet avec un **README**
- Comprendre les **limites du relationnel en termes de passage à l'échelle (scalabilité)**

#### Contexte du projet à réaliser 

Vous devez développer une application web permettant de gérer des données issues d’un **cas d’application au choix**. 

##### Quelques exemples de cas possibles (liste non exhaustive)  :

- Gestion de films / séries
- Association sportive
- Bibliothèque musicale
- Médiathèque
- Jeux vidéo
- Restaurant / menus
- Gestion d’étudiants / formations

**Le thème est libre**, mais doit être validé.

##### Contraintes techniques

1. Langage : **PHP 8.x**
2. Accès base de données : **PDO**
3. Base de données : **MySQL / MariaDB**
4. Serveur local : XAMPP / WAMP / MAMP
5. Gestion de version : **Git (obligatoire)**


##### Organisation du projet

Votre projet doit contenir au minimum :

##### Travail demandé

######  Dépôt Git (obligatoire)
1. Créer un **dépôt Git** (GitHub / GitLab)
2. Effectuer des **commits réguliers**
3. Chaque commit doit avoir un **message explicite**

**_Attention : un projet avec peu de commit sera pénalisé._**

##### Modélisation de la base de données

Vous devez fournir :

1. un **schéma relationnel**
2. un script SQL `schema.sql`

Le schéma doit contenir **au minimum** :

1. Une relation 1–1
2. Une relation 1–N
3. Une relation N–N

##### Conclusion

Cette SAE vise à vous placer dans une **situation proche du monde professionnel**, en combinant :
1. développement,
2. bases de données,
3. gestion de projet,
4. réflexion sur la scalabilité.


##### Bonus – Limites et ouverture NoSQL, Not Only SQL 

###### Objectif du bonus

Montrer que l’application **ne passe pas à l’échelle** dans certains cas.

###### Travail demandé

1. Décrire un **scénario de forte montée en charge** :
- grand volume de données
- nombreuses relations
- requêtes coûteuses
2. - Expliquer :
    - pourquoi le modèle relationnel devient limitant
    - quelles requêtes posent problème
- Proposer **une alternative NoSQL** (MongoDB, par exemple) :
    - sans implémentation
    - uniquement conceptuelle

##### Livrables attendus
- Lien vers le **dépôt Git**
- Application fonctionnelle
- Script SQL
- README.md complet

----
##### Grille d'évaluation à titre indicative 

| Critère                  | Pondération |
| ------------------------ | ----------- |
| Modélisation de la base  | 25 %        |
| Utilisation de PHP / PDO | 25 %        |
| Relations SQL            | 20 %        |
| Git & commits            | 15 %        |
| README & documentation   | 10 %        |
| Bonus NoSQL              | +5 %        |

##### Grille d'évaluation par les pairs


##### Echéances :
- Constitution des groupes
- Mettre un lien pour renseigner les dépôts Git
- Validation du sujet  et du cas d'utilisation 
