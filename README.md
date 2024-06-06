# Petit guide d’accessibilité pour site Web 

(MAJ - 2024-06-03).

Ce guide est dédié aux bonnes pratiques d'accessibilité pour les sites Internet en vous donnant de petits conseils pratiques pour garantir que votre site offre une **accessibilité optimale**. Il vise à fournir des directives **claires** pour améliorer la réflexion et puis la conception des menus, textes et titres, formulaire sur votre site web et les futurs pages qui y seront créées.

> Il devient **impératif** de créer des espaces en ligne inclusifs, où chacun, indépendamment de ses capacités visuelles et auditives, peut accéder à l'information de manière efficace et équitable. 

Pour optimiser un site internet, il est essentiel de faciliter l’accès aux informations pour l’ensemble des utilisatrices et utilisateurs, et bien sûr, cela concerne aussi les personnes en situation de handicap quel qu'il soit.

La conception d'un site accessible ne se limite pas à une simple conformité aux normes, mais s'étend à la création d'une expérience en ligne enrichissante pour tous les utilisateurs. En se concentrant sur des aspects tels que la lisibilité, la navigation simplifiée et la compréhension du contenu, nous pouvons créer des environnements web où chacun peut pleinement participer, quelle que soit sa capacité visuelle et/ou auditive.

Ce guide fournira des petits conseils pratiques pour garantir que notre site offre une accessibilité optimale.


## Exemple de différents problèmes visuels rencontrées (liste qui donne quelques indications, quelques pistes, mais qui peut encore être complétée).

Les problèmes visuels peuvent varier considérablement d'une personne à l'autre et ils peuvent être permanents ou temporaires. Voici quelques-uns des problèmes visuels les plus courants qui peuvent affecter nos internautes :

**1** - **Cécité totale** : Certains utilisateurs sont totalement aveugles et donc ne peuvent pas voir du tout.

**2** - **Daltonisme** : Les personnes atteintes de daltonisme ont des difficultés à distinguer certaines couleurs. Les formes les plus courantes de daltonisme affectent la capacité à différencier le rouge et le vert (8% des hommes sont daltoniens).

**3** – **Dyslexie** :  La dyslexie se définit comme une confusion et/ou inversion de sons et de lettres. Ce trouble de la lecture se traduit par une difficulté à identifier certaines lettres et mots écrits.

**4** - **Presbytie** : La presbytie est un problème de vision souvent lié à l'âge qui rend difficile la mise au point sur des objets, textes ou images proches.

**5** - **Photophobie** : Certains utilisateurs sont sensibles à la lumière et peuvent trouver difficile de lire du texte sur un fond lumineux/blanc.

**6** – Problème auditif : Cela peut aller de la perte auditive modérée, légère, voir même sévère ou profonde. Les personnes ayant des problèmes d’audition peuvent avoir du mal à entendre les paroles prononcées dans les vidéos/podcast/etc. du site Internet. Il est aussi possible que certaines personne ne peuvent tout simplement pas écouter des sons trop fort ou même n’en rien entendre du tout.

Il est important de prendre en compte cette diversité de problèmes visuels/auditifs lors de la conception ou l’amélioration d'un site web afin de le rendre accessible au plus grand nombre d'utilisateurs possible. 

L'application de bonnes pratiques en matière d'accessibilité contribuera à améliorer l'expérience pour tous les utilisateurs, indépendamment de leurs capacités.


# **Comment tester un site Web**

> La vérification de l’accessibilité doit être effectué par des **tests manuels** avec des outils dédiés dans le but de rendre les sites Internet et les services numériques accessibles à toutes et à tous. 



## LES EXTENTIONS UTILISÉES POUR LES TESTS : 

Il est tout à fait possible de simuler les déficits visuels et se rendre compte des améliorations à apporter à notre site via quelques extensions des navigateurs Web comme Google Chrome et également de sites web d’analyse. 
**Le Site de l’Office de Tourisme de Martigues (www.martigues-tourisme.com) servira d’exemple pour la suite de ce guide.**

> [!TIP]
> Liste non exhaustive d'extension. Elles sont ici à titre d'exemple et elles sont utilisées dans un format **gratuit**.

### 1 - Funkify – Disability Simulator (disponible en extension sur google chrome -> Funkify Disability Simulator pour Chrome )

Funkify est une extension pour Chrome qui vous permettra de découvrir votre site Web et ses interfaces à travers les yeux de personnes ayant des capacités et des handicaps différents. Elle existe uniquement en anglais. Mais elle est facile à utiliser.

![image](https://github.com/ZeCrusher/Accessibilit-sur-le-Web/assets/102222839/0e7da314-43de-4ca0-920f-8ce1a9f94257)

Pour simuler un handicap, il suffit d’ouvrir l’extension en cliquant sur son icone dans Chrome, en haut à droite, puis de choisir une « simulation d’handicap » avec le bouton Star. Dans la version gratuite, vous ne pouvez pas additionner les handicaps.

### 2 – Heandingsmaps (Lien Headingsmap pour Chrome)

**Heandingsmaps** est une extension qui permet d’afficher et de parcourir facilement les menus d’un site Internet et d’auditer la hiérarchie des titres. Cela est rendu possible grâce aux balises html ``` <h1>,<h2>, <ol>, <li> ``` 

Exemple d’un menu avec les balises h1 et h2. 

![image](https://github.com/ZeCrusher/Accessibilit-sur-le-Web/assets/102222839/4e15a1e6-12e9-4c81-9250-0db9262ee447)

Nous avons ici sur notre Extranet de l'office de Tourisme une hiérarchie correctement affichée. Le menu de la page d’accueil et l’arborescence sont bien visibles sur application Heandingsmaps et cela permet un bon parcourt du site.

Contrairement au site martigues-tourisme où aucun menu et sous menu ne sont visible :
![image](https://github.com/ZeCrusher/Accessibilit-sur-le-Web/assets/102222839/f801429c-67eb-4692-9bdb-1284196516ea)


### 3 - Web Disability Simulator Sélection : (Lien chrome : Web Disability)  

Web Disability Simulator est une extension de Google Chrome qui simule la façon dont les utilisateurs peuvent consulter une page Web. Le simulateur crée une expérience qui vous permet de mieux comprendre l'importance de l'accessibilité du Web. 

Handicap simulé :
-	Différents types de défauts de vision des couleurs.
-	Vision tunnel ou hypermétropie. 
-	Web sous un fort soleil. 
-	Parkinson.
-	Dyslexie ou petit vocabulaire.
-	Difficultés de concentration.

> Exemple d’une simulation de l’extension avec le menu du site de l’Office de Tourisme. Le bouton Menu n’est pas assez visible pour un internaute ayant un défaut de vision des couleurs.

![image](https://github.com/ZeCrusher/Accessibilit-sur-le-Web/assets/102222839/c4b69865-82ba-49d2-8366-6fbc7c00bca8)


#### 4 - Site WebAIM (Site : Wave.webaim avec Martigues-tourisme.com en exemple d’analyse) : 

WebAIM (Web Accessibility In Mind) propose des solutions complètes d'accessibilité Web. Il analyse complètement un site et indique les bonnes et mauvaises structures d’accessibilités en affichant les erreurs via des icones directement sur la page du site. Il propose également une solution pour les corriger. Il indique également les bonnes pratiques du site.

![image](https://github.com/ZeCrusher/Accessibilit-sur-le-Web/assets/102222839/3a9635f9-1bab-43f4-988a-57a9dd85e894)


# Mise en situation et test du site www.martigues-tourisme.com


Dans le cadre d’un engagement continu envers l’accessibilité et l'inclusion, nous allons voir dans une petite présentation quelques améliorations à apportées à notre site internet. L’objectif principal est d'accroître l'accessibilité, faisant de notre plateforme un espace accueillant et fonctionnel pour tous les utilisateurs, indépendamment de leurs capacités ou de leurs besoins particuliers.

A - Respecter les balises titre et les sous-titres des pages
B – Mieux comprendre les couleurs des pages, titres et leurs contrastes.
C – L’accessibilité des images et vidéos.

## A - RESPECTER LES BALISES TITRE ET LES SOUS-TITRES DES PAGES

L’ACCESSIBILITE DES MENUS :
Structuration logique : Utilisez une structure de menu logique et hiérarchique. Les sous-menus doivent être clairement associés à leurs menus parents. 

Nous allons utiliser l’extension Heandingsmaps qui permet d’identifier l’arborescence d’un site Web et d’en extraire les textes de menu et d’en faire des liens directs vers les pages et les liens. 


