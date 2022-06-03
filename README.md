# Référentiels des Archives nationales de France

Les référentiels des Archives nationales de France | the Archives nationales de France authority data and vocabularies


## Téléchargement

Télécharger la dernière release (la version 1.1, juin 2022): [https://github.com/ArchivesNationalesFR/Referentiels/releases/tag/1.1](https://github.com/ArchivesNationalesFR/Referentiels/releases/tag/1.1)

## Description 

Formats :
- XML/RDF pour l'ensemble des référentiels. Principaux modèles utilisés : [SKOS](https://www.w3.org/2004/02/skos/) et [Records in Contexts - Ontology (RiC-O)](https://www.ica.org/standards/RiC/ontology) (dans sa dernière version officielle en date, la v0.2 de février 2021)
- [XML/EAC-CPF](https://eac.staatsbibliothek-berlin.de/schemata-and-tag-library/) pour les notices du référentiel des producteurs
- CSV (encodage UTF-8; séparateur de champs : virgule ; valeurs des colonnes encadrées par des guillemets ('"')) pour les concepts et les lieux. Ces fichiers CSV ont été produits à partir des versions RDF. Pour les agents, les fichiers CSV fournis sont des listes, qui ne contiennent pas toute la substance des notices RDF des agents.

En cours de construction | a work in progress...

Licence | License : Ces métadonnées étant des informations publiques, l'usager dispose d'un droit non exclusif et gratuit de libre « réutilisation » à des fins commerciales ou non, dans le monde entier et pour une durée illimitée. Il doit accompagner chaque rediffusion des informations de l'indication précise de l'origine des métadonnées : « Archives nationales (France) », date de ces métadonnées (mai 2022), nom du référentiel (fourni dans le fichier Excel qui en donne la liste). Voir à ce sujet la page : https://www.archives-nationales.culture.gouv.fr/fr/web/guest/reutilisation-des-donnees-publiques.

La liste fournie (fichier [Liste-referentiels.xlsx](https://github.com/ArchivesNationalesFR/Referentiels/blob/main/Liste-referentiels.xlsx)) donne diverses informations sur chacun de ces référentiels.

## Avertissements

Les référentiels sont **en construction**, ce qui veut dire qu'ils sont en règle générale très incomplets : il y manque la description de nombreuses entités, et les descriptions fournies sont parfois pauvres. Ils sont cependant utilisés, dans un format propre au SI des Archives nationales, pour indexer la description des archives que l'institution conserve, ou pour contextualiser cette description, ce qui permet de construire progressivement des points d'accès pour les utilisateurs finaux. Des efforts collectifs conséquents permettent actuellement d'enrichir ces référentiels, et leur enrichissement constitue un des objectifs du plan stratégique des Archives nationales pour 2021-2025. Comme depuis plusieurs années ils s'avèrent utiles voire nécessaires pour divers projets dépassant le cadre institutionnel des Archives nationales ou pour des équipes extérieures aux Archives nationales (comme ALEGORIA - voir à ce sujet [https://github.com/ArchivesNationalesFR/ALEGORIA-datasets](https://github.com/ArchivesNationalesFR/ALEGORIA-datasets)), nous avons considéré utile de les publier, et d'en proposer régulièrement ici des mises à jour. 

**La version des référentiels la plus riche, que nous recommandons d'utiliser est la version RDF (fichiers d'extension .rdf)**, qui est conforme aux standards RDF, SKOS et RiC-O. 

Nous prévoyons de publier bientôt au moins une partie de ces fichiers sur [https://data.culture.gouv.fr](https://data.culture.gouv.fr).


Les Archives nationales ne disposent pas à ce jour d'application web leur permettant de publier et de rendre accessibles aux humains et aux machines (sparql end point) leurs référentiels au format RDF/XML. Par conséquent **les IRIs des entités décrites dans ces référentiels - celles commençant par http://data.archives-nationales.culture.gouv.fr/, segment de base fourni dans l'attribut xml:base de l'élément racine rdf:RDF de chaque fichier) -  ne sont pas déréférençables**. La partie variable de ces IRIs utilise cependant l'identifiant unique et pérenne de l'entité décrite dans la version de ces référentiels qui est interne aux Archives nationales. 

## For more information | Pour plus d'informations

You can contact the Lab of the Archives Nationales de France by email at the following address: <le-lab.archives-nationales@culture.gouv.fr>.
Vous pouvez contacter par courriel le Lab des Archives nationales de France, à l'adresse suivante :  <le-lab.archives-nationales@culture.gouv.fr>.

