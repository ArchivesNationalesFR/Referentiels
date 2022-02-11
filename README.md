# Référentiels des Archives nationales de France

Les référentiels des Archives nationales de France | the Archives nationales de France authority data and vocabularies

Version : 1.0, décembre 2021

Formats : 

- XML/RDF pour l'ensemble des référentiels. Principaux modèles utilisés : [SKOS](https://www.w3.org/2004/02/skos/) et [Records in Contexts - Ontology (RiC-O)](https://www.ica.org/standards/RiC/ontology)
- [XML/EAC-CPF](https://eac.staatsbibliothek-berlin.de/schemata-and-tag-library/) pour les notices du référentiel des producteurs

En cours de construction | a work in progress...

Licence | License : Ces métadonnées étant des informations publiques, l'usager dispose d'un droit non exclusif et gratuit de libre « réutilisation » à des fins commerciales ou non, dans le monde entier et pour une durée illimitée. Il doit accompagner chaque rediffusion des informations de l'indication précise de l'origine des métadonnées : « Archives nationales (France) », date des métadonnées (mai 2021), nom du référentiel (fourni dans le fichier Excel qui en donne la liste). Voir à ce sujet la page : https://www.archives-nationales.culture.gouv.fr/fr/web/guest/reutilisation-des-donnees-publiques.


La liste fournie (fichier [Liste-referentiels.xlsx](https://github.com/ArchivesNationalesFR/Referentiels/blob/main/Liste-referentiels.xlsx)) donne diverses informations sur chacun de ces référentiels.

## Avertissements

Les référentiels sont **en construction**, ce qui veut dire qu'ils sont en règle générale très incomplets : il y manque la description de nombreuses entités, et les descriptions fournies sont parfois pauvres. Ils sont cependant utilisés, dans un format propre au SI des Archives nationales, pour indexer la description des archives que l'institution conserve, ou pour contextualiser cette description, ce qui permet de construire progressivement des points d'accès pour les utilisateurs finaux. Des efforts collectifs conséquents permettent actuellement d'enrichir ces référentiels, et leur enrichissement constitue un des objectifs du plan stratégique des Archives nationales pour 2021-2025. Comme depuis plusieurs années ils s'avèrent utiles voire nécessaires pour divers projets dépassant le cadre institutionnel des Archives nationales ou pour des équipes extérieures aux Archives nationales, nous avons considéré utile de les publier, et d'en proposer régulièrement ici des mises à jour. Nous avons choisi pour ce faire le format RDF, sans exclure d'autres formats. Nous prévoyons d'en publier bientôt au moins la partie la plus riche sur [https://data.culture.gouv.fr](https://data.culture.gouv.fr).


Les Archives nationales ne disposent pas à ce jour d'application web leur permettant de publier et de rendre accessibles aux humains et aux machines (sparql end point) leurs référentiels au format RDF/XML. Par conséquent **les IRIs des entités décrites dans ces référentiels - celles commençant par http://data.archives-nationales.culture.gouv.fr/, segment de base fourni dans l'attribut xml:base de l'élément racine rdf:RDF de chaque fichier) -  ne sont pas déréférençables**. La partie variable de ces IRIs utilise cependant l'identifiant unique et pérenne de l'entité décrite dans la version de ces référentiels qui est interne aux Archives nationales. 

## Pour plus d'informations

Vous pouvez contacter par courriel le Lab des Archives nationales de France, à l'adresse suivante :  <le-lab.archives-nationales@culture.gouv.fr>.
