# Référentiels des Archives nationales de France

Les référentiels des Archives nationales de France | the Archives nationales de France authority data and vocabularies


## Téléchargement

Télécharger la dernière release (la version 1.1, juin 2022): [https://github.com/ArchivesNationalesFR/Referentiels/releases/tag/1.1](https://github.com/ArchivesNationalesFR/Referentiels/releases/tag/1.1)

**Noter qu'une version 2.0 est en cours de finalisation. Elle sera très différente de la v 1.1 (plus de données sur les entités déjà décrites, mise en conformité avec RiC-O 1.1). Si vous vous intéressez à ces données, nous vous recommandons vraiment d'attendre la release de la version 2, que nous publierons vers la mi-juin 2026.**

## La recherche et la consultation de ces données sont désormais possibles sur le web !

Retrouvez le dernier état en date des données via l'application **Garance** (version 1 publiée fin avril 2026) : [https://rdf.archives-nationales.culture.gouv.fr/garance](https://rdf.archives-nationales.culture.gouv.fr/garance).

Elles bénéficient aussi d'un accès SPARQL, via une instance du triplestore QLever :

-  le SPARQL endpoint a pour adresse [https://sparql.archives-nationales.culture.gouv.fr/garance/sparql](https://sparql.archives-nationales.culture.gouv.fr/garance/sparql).
-  son interface utilisateur est accessible à [https://sparql.archives-nationales.culture.gouv.fr/garance](https://sparql.archives-nationales.culture.gouv.fr/garance). Vous y trouverez en particulier des exemples de requêtes (cliquer sur le bouton "Examples"). Vous pourrez partager les URL de vos requêtes (cliquer sur le bouton "Share").


## Description 

Formats :
- XML/RDF pour l'ensemble des référentiels. Principaux modèles utilisés : [SKOS](https://www.w3.org/2004/02/skos/) et [Records in Contexts - Ontology (RiC-O)](https://www.ica.org/standards/RiC/ontology) 
- [XML/EAC-CPF](https://eac.staatsbibliothek-berlin.de/schemata-and-tag-library/) pour les notices du référentiel des producteurs
- CSV (encodage UTF-8; séparateur de champs : virgule ; valeurs des colonnes encadrées par des guillemets ('"')) pour les concepts. Ces fichiers CSV ont été produits à partir des versions RDF. Pour les agents, les fichiers CSV fournis sont des listes, qui ne contiennent pas toute la substance des notices RDF des agents.

En cours de construction | a work in progress...

Licence | License : Ces métadonnées étant des informations publiques, l'usager dispose d'un droit non exclusif et gratuit de libre « réutilisation » à des fins commerciales ou non, dans le monde entier et pour une durée illimitée. ll doit accompagner chaque rediffusion des informations de l’indication précise de l’origine des métadonnées (« Archives nationales de France » et de la date de ces métadonnées (actuellement 2026).

Dans le cas où l’utilisateur souhaite citer la description d’une entité (agent, concept ou lieu) publiée dans Garance, il est invité à utiliser l’URI de l’entité, tel qu’il est affiché sur la page web de Garance et tel qu’on le trouve dans le fichier RDF source. 

Par exemple, pour citer la description de Simone Veil dans Garance, il convient d’écrire : « Description de Simone Veil (1927-2017) dans le site web Garance de diffusion des référentiels sémantisés des Archives nationales de France : [https://rdf.archives-nationales.culture.gouv.fr/agent/009941](https://rdf.archives-nationales.culture.gouv.fr/agent/009941) ».

## Avertissements

Les référentiels sont **en construction**, ce qui veut dire qu'ils sont en règle générale très incomplets : il y manque la description de nombreuses entités, et les descriptions fournies sont parfois pauvres. Ils sont cependant utilisés, dans un format propre au SI des Archives nationales, pour indexer la description des archives que l'institution conserve, ou pour contextualiser cette description, ce qui permet de construire progressivement des points d'accès pour les utilisateurs finaux. Des efforts collectifs conséquents permettent actuellement d'enrichir ces référentiels, et leur enrichissement constitue un des objectifs du plan stratégique des Archives nationales. Comme depuis plusieurs années ils s'avèrent utiles voire nécessaires pour divers projets dépassant le cadre institutionnel des Archives nationales ou pour des équipes extérieures aux Archives nationales (comme ALEGORIA entre 2018 et 2021 - voir à ce sujet [https://github.com/ArchivesNationalesFR/ALEGORIA-datasets](https://github.com/ArchivesNationalesFR/ALEGORIA-datasets), et plus récemment [ORESM](https://oresm.hypotheses.org/) et [AGAPE](https://agape-anr.github.io/)), nous avons considéré utile de les publier, et d'en proposer régulièrement ici des mises à jour. 

**La version des référentiels la plus riche, que nous recommandons d'utiliser est la version RDF (fichiers d'extension .rdf)**, qui est conforme aux standards RDF, SKOS et RiC-O. 

## For more information | Pour plus d'informations

You can contact the Lab of the Archives Nationales de France by email at the following address: <le-lab.archives-nationales@culture.gouv.fr>.
Vous pouvez contacter par courriel le Lab des Archives nationales de France, à l'adresse suivante :  <le-lab.archives-nationales@culture.gouv.fr>.

