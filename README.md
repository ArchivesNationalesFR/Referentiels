# Référentiels des Archives nationales de France

Les référentiels des Archives nationales de France | the Archives nationales de France authority data and vocabularies

## Le contenu en quelques mots

- 18 394 notices d’agents (des collectivités, des personnes et des familles)
- 54 121 notices de lieux (parmi lesquels les circonscriptions administratives françaises contemporaines et un nombre conséquent de lieux de Paris, dont 13 819 voies)
- 13 listes d’autorité et thésauri, décrivant en tout 3559 concepts

## Téléchargement des données

Télécharger la dernière release (la version 2.0, octobre 2026) : https://github.com/ArchivesNationalesFR/Referentiels/releases/tag/2.0

**Cette version 2.0 est très différente de la v 1.1 (plus de données sur les entités déjà décrites, plus d’entités, mise en conformité avec RiC-O 1.1). Pour plus d’informations sur ce qui a été fait, vous pouvez consulter les notes de la release et [la page "le projet" du site web Garance](https://rdf.archives-nationales.culture.gouv.fr/garance/pages/fr/project/)**.

## La recherche et la consultation de ces données sont désormais possibles sur le web !

Retrouvez le dernier état en date des données via l’application **Garance** : [https://rdf.archives-nationales.culture.gouv.fr/garance](https://rdf.archives-nationales.culture.gouv.fr/garance).

Elles bénéficient aussi d’un accès SPARQL, via une instance du triplestore QLever :

-  le SPARQL endpoint a pour adresse [https://sparql.archives-nationales.culture.gouv.fr/garance/sparql](https://sparql.archives-nationales.culture.gouv.fr/garance/sparql).
-  son interface utilisateur est accessible à [https://sparql.archives-nationales.culture.gouv.fr/garance](https://sparql.archives-nationales.culture.gouv.fr/garance). Vous y trouverez en particulier des exemples de requêtes (cliquer sur le bouton "Examples"). Vous pourrez partager les URL de vos requêtes (cliquer sur le bouton "Share").


## Description 

Formats :
- XML/RDF pour l’ensemble des référentiels. Principaux modèles utilisés : [SKOS](https://www.w3.org/2004/02/skos/) et [Records in Contexts - Ontology (RiC-O)](https://www.ica.org/standards/RiC/ontology), dans la dernière version officielle en date, la version 1.1 de mai 2025. Une petite extension de RiC-O a par ailleurs été produite pour ajouter à cette ontologie de domaine très générique quelques propriétés utiles dans le cadre de ce travail. Cette ontologie est accessible [ici](https://github.com/ArchivesNationalesFR/ontology). 
- [XML/EAC-CPF](https://eac.staatsbibliothek-berlin.de/schemata-and-tag-library/) pour les notices d’agents issues du référentiel des producteurs
- CSV (encodage UTF-8 ; séparateur de champs : virgule ; valeurs des colonnes encadrées par des guillemets ('"')). Ces fichiers CSV ont été produits à partir des versions RDF. Pour les agents et les lieux, ces fichiers CSV ne sont que des listes, qui sont loin de contenir toute la substance des notices RDF.

En cours de construction | a work in progress...

Licence | License : Ces métadonnées étant des informations publiques, l’usager dispose d’un droit non exclusif et gratuit de libre « réutilisation » à des fins commerciales ou non, dans le monde entier et pour une durée illimitée. ll doit accompagner chaque rediffusion des informations de l’indication précise de l’origine des métadonnées (« Archives nationales de France » et de la date de ces métadonnées (actuellement 2026)).

Dans le cas où l’utilisateur souhaite citer la description d’une entité (agent, concept ou lieu), il est invité à utiliser l’URI de l’entité, tel qu’il est affiché sur la page web de Garance et tel qu’on le trouve dans le fichier RDF source. 

Par exemple, pour citer la description de Simone Veil dans Garance, il convient d’écrire : « Description de Simone Veil (1927-2017) dans le site web Garance de diffusion des référentiels sémantisés des Archives nationales de France : [https://rdf.archives-nationales.culture.gouv.fr/agent/009941](https://rdf.archives-nationales.culture.gouv.fr/agent/009941) ».

## Avertissements

Les référentiels sont **en construction**, ce qui veut dire qu’ils sont en règle générale très incomplets : il y manque la description de nombreuses entités, et les descriptions fournies sont parfois pauvres. Ils sont cependant utilisés, dans un format propre au SI des Archives nationales, pour indexer la description des archives que l’institution conserve, ou pour contextualiser cette description, ce qui permet de construire progressivement des points d’accès pour les utilisateurs finaux. Des efforts collectifs conséquents permettent actuellement d’enrichir ces référentiels, et leur enrichissement constitue un des objectifs du plan stratégique des Archives nationales. Comme depuis plusieurs années ils s’avèrent utiles voire nécessaires pour divers projets dépassant le cadre institutionnel des Archives nationales ou pour des équipes extérieures aux Archives nationales (comme ALEGORIA entre 2018 et 2021 - voir à ce sujet [https://github.com/ArchivesNationalesFR/ALEGORIA-datasets](https://github.com/ArchivesNationalesFR/ALEGORIA-datasets), et plus récemment [ORESM](https://oresm.hypotheses.org/) et [AGAPE](https://agape-anr.github.io/)), nous avons considéré utile de les publier, et d’en proposer régulièrement ici des mises à jour. 

**La version des référentiels la plus riche, que nous recommandons d’utiliser, est la version RDF (fichiers d’extension .rdf)**. 

Nous prévoyons d’ajouter à chacun des vocabulaires contrôlés et à chacune des notices d’entités une propriété pour spécifier un score de qualité.

## For more information | Pour plus d’informations

You can contact the Lab of the Archives Nationales de France by email at the following address: <le-lab.archives-nationales@culture.gouv.fr>.
Vous pouvez contacter par courriel le Lab des Archives nationales de France, à l'adresse suivante :  <le-lab.archives-nationales@culture.gouv.fr>.

