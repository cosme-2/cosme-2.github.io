---
layout: default
title: Annexe 4. Modèle des métadonnées
parent: Guide FAIR
nav_order: 7
---

# Annexe 4. Modèle (prévisionnel) des métadonnées
{: .no_toc }

---

[FAIR. Modèle des métadonnées.docx](/assets/doc/FAIR.docx){: .btn .btn-blue .fw-300 .text-grey-lt-000 .float-left .mr-2 }

télécharger le modèle des métadonnées FAIR
{: .fs-4 .fw-300 }

---

**Rappel:** Il est utile de rappeler que les principes FAIR ne sont que des recommandations qui visent à rendre les données scientifiques plus accessibles et plus compréhensibles et leurs sauvegarde et réutilisation plus pérennes. La _FAIRititude_ [FAIRness] complète des données n’est cependant qu’un objectif théorique difficilement atteignable (sur ce point, voir la bibliographie [[2](/docs/fair-guide/bibliography#2){:target="_blank"}], [[3](/docs/fair-guide/bibliography#3){:target="_blank"}], [[10](/docs/fair-guide/bibliography#10){:target="_blank"}], [[12](/docs/fair-guide/bibliography#12){:target="_blank"}]). Par conséquent, chaque champ des métadonnées doit être rempli le plus complètement possible, mais dans des limites raisonnables.
{: .fw-300 }

| Champ    				    | Correspondance éléments Dublin Core   | Correspondance champs Zenodo  	    |
:---------------------------|:--------------------------------------|:--------------------------------------|
| Identifiant (PID): <span class="further-description">(L’identifiant est attribué automatiquement par le dépôt lors de la mise en ligne.)</span>  |  DC.Identifier   					  | Digital Object Identifier<sup class="required-field">+</sup>     		  |
| Date de la mise en ligne (des données):   |  DC.Date   							  | Publication date<sup class="required-field">+</sup>   |
| Intitulé (du jeu de données du corpus):  |  DC.Title   		   					  | Title<sup class="required-field">+</sup>   |
| Auteur(s) du corpus (affiliation): <span class="further-description">(Par “l’auteur du corpus” on entend la ou les personne(s) qui ont créé le jeu de données et non la ou les personne(s) qui ont écrit les textes des documents contenus dans le corpus. Par exemple, si Jean-Paul Machin, chercheur au CNRS, a créé le corpus qui contient les textes de Dante Alighieri, on retient, comme auteur du corpus, J.-P.Machin et non Dante Alighieri.)</span>  |  DC.Creator   						  | Authors<sup class="required-field">+</sup>   |
| Contributeur(s) (affiliation, rôle): <span class="further-description">(Il s’agit de toutes les personnes qui ont contribué, d'une façon ou d'une autre, à l’élaboration du corpus. Voir infra la liste des différents rôles possibles des contributeurs telle qu’elle est proposée par le dépôt Zenodo.)<sup style="font-size: 14px; font-weight: bold;">*</sup></span> | DC.Contributeur 					  | Contributors    |
| Description (des données): <span class="further-description">(Présenter ici le corpus, ces données, le programme de recherche qui a permis la construction de ce corpus, etc.)</span>  |  DC.Description  					  |  Description<sup class="required-field">+</sup>   |
| Format de fichier (FAIR: I1): <span class="further-description">(Voir: [Liste of file formats](https://en.wikipedia.org/wiki/List_of_file_formats){:target="_blank"}.)</span>  |  DC.Format   						  | <span class="small-italic">(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)</span>   |
| Logiciels spécifiques nécessaires pour la lecture des données: (nom, version, système d’exploitation) (FAIR: I1): <span class="further-description">(Par exemple des logiciels de lexicométrie pour les données lexicostatistiques ou des logiciels de l’analyse de réseaux pour les données prosopographiques, etc. Les logiciels de traitement de texte (format doc, txt, csv, etc.), de bases de données (format sql), de visionnage des images (jpg, tiff, etc.), de lecture des fichiers XML (sauf des cas particuliers comme, par exemple, les logiciels lexicométriques TXM ou Philologic4 qui s’appuient sur un formatage XML particulier), etc. ne sont pas des logiciels spécifiques et ils ne doivent pas être mentionnés.)</span>  |    									  |  <span class="small-italic">(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)</span>   |
| Si format ou logiciel particulier, expliquer clairement pourquoi ils ont été choisis (FAIR: I1):  |     									  |  <span class="small-italic">(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)</span>   |
| Si les données ne sont pas explicites en l’état, renvoyer vers les explications / documentation / vocabulaire pour expliciter les données (FAIR: I2):  |    						   			  |  <span class="small-italic">(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)</span>   |
| Provenance et historique des données (FAIR R.1.2): <span class="further-description">(Il s’agit d’indiquer l’historique et la provenance d'un jeu de données en tant qu’objet digital. Par exemple, les données peuvent être produites lors d’un autre projet et ensuite réutilisées, corrigées et modifiées par le présent projet. Le contenu de ce champ peut, par exemple, être le suivant: “Les données qui concernent les VIII<sup>e</sup> et IX<sup>e</sup> siècles ont été extraites d’un jeu de donnée sous format sql produit lors du projet “X” et corrigées ensuite par Monsieur Untel. Les données qui concernent le XII<sup>e</sup> siècle ont été extraites d’un jeu de donnée sous format xml produit lors du projet “Y” sans aucune correction supplémentaire. Toutes les autres données ont été saisies manuellement par Monsieur Unautre et Madame Uneautre sous format des documents JSON dans la base MongoDB”. Pour plus de détail sur la notion de la provenance des données, voir par exemple: [rd-alliance/Indicators for R1.2](https://github.com/rd-alliance/FAIR-data-maturity-model-WG/issues/28){:target="_blank"}.)</span>  |     									  |  <span class="small-italic">(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)</span>   |
| Standards, conventions des données utilisées (FAIR: R1.3): <span class="further-description">(Bien qu’un “standard” commun ne semble pas exister en sciences humaines et sociales, certains projets ou programmes peuvent s’appuyer sur des conventions similaires. Par exemple, l’organisation des données dans le même type de tableau, l’utilisation des mêmes principes de balisage, etc.)</span>  |     									  |  <span class="small-italic">(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)</span>   |
| Version (des données): <span class="further-description">(Il est conseillé d’utiliser la nomencalutre du “versioning semantic”. Pour plus de détails sur le “versioning semantic” voir [Semantic Versioning](https://semver.org/){:target="_blank"}.)</span>  |     									  |  Version   |
| Langue principale des données: <span class="further-description">(Si, par exemple, les textes sont en latin, mais ils sont accompagnés par les analyses en français, on indique ici la langue principale des données qui est donc le latin.)</span>  |  DC.Language   						  |  Language   |
| Mots-clés:   |  DC.Subject   						  |  Keywords   |
| Droit d'accès et licence des données (FAIR: R1.1): <span class="further-description">(Il existe différents types du droit d’accès et de licences. Voir infra la liste des droits d’accès proposée par le dépôt Zenodo. Le nombre de différentes licences est bien trop élevé pour les mentionner toutes.)<sup style="font-size: 14px; font-weight: bold;">**</sup></span>  |  DC.Rights   						  |  Access right & License<sup class="required-field">+</sup>   |
| Financement(s): <span class="further-description">(Il s'agit de tous les financements qui ont permis l’élaboration de ce corpus.)</span>  |     									  |  Funding / Grants   |
| Données liées (FAIR: I3): <span class="further-description">(Mentionner, le cas échéant, le PID, l’intitulé des données liées et le type de lien. Par exemple: <br/> “ces textes (PID, intitulé du jeu de données avec les textes) <u>est la transcription</u> de ces photos de manuscrits (PID, intitulé du jeu de données avec les images)”.)</span>  |   DC.Relation   						  |  Related/alternate identifiers   |

__<sup style="color:red;">+</sup>__ Champ obligatoire dans le dépôt de données Zenodo.
{: .lh-1 .fs-2 .text-grey-dk-100 }

__\*__ **<u>Liste des rôles des contributeurs (proposé par le dépôt Zenodo):</u>**
{: .lh-1 .fs-2 .text-grey-dk-100 }
- Contact person
- Data collector
- Data curator
- Data manager
- Distributor
- Editor
- Hosting institution
- Other
- Producer
- Project leader
- Project manager
- Project member
- Registration authority
- Related person
- Research group
- Researcher
- Rights holder
- Sponsor
- Supervisor
- Work package leader
{: .lh-1 .ml-2 .fs-2 .text-grey-dk-100 }

__\*\*__ **<u>Les différents types des droits d’accès (proposé par le dépôt Zenodo):</u>**
{: .lh-1 .fs-2 .text-grey-dk-100 }
- Open Access 
- Embargoed Access 
- Restricted Access 
- Closed Access 
{: .lh-1 .ml-2 .fs-2 .text-grey-dk-100 }

---

#### À suivre: [Annexe 5. Questionnaire détaillé](/docs/fair-guide/annexe-5)
{: .no_toc .text-right .fs-3 .fw-400 .text-grey-dk-100 }
