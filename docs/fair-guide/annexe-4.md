---
layout: default
title: Annexe 4. Modèle des métadonnées
parent: Guide FAIR
nav_order: 7
---

# Annexe 4. Modèle (prévisionnel) des métadonnées
{: .no_toc }

**Rappel:** Il est utile de rappeler que les principes FAIR ne sont que des recommandations qui visent à rendre les données scientifiques plus accessibles et plus compréhensibles et leurs sauvegarde et réutilisation plus pérennes. La _FAIRititude_ [FAIRness] complète des données n’est cependant qu’un objectif théorique difficilement atteignable (sur ce point, voir la bibliographie [[2](/docs/fair-guide/bibliography#2){:target="_blank"}], [[3](/docs/fair-guide/bibliography#3){:target="_blank"}], [[10](/docs/fair-guide/bibliography#10){:target="_blank"}], [[12](/docs/fair-guide/bibliography#12){:target="_blank"}]). Par conséquent, chaque champ des métadonnées doit être rempli le plus complètement possible, mais dans des limites raisonnables.
{: .fw-300 }

| Champ    				    | Qualité  							  				  | Correspondance éléments Dublin Core   | Correspondance champs Zenodo  	      |
:---------------------------|:----------------------------------------------------|:--------------------------------------|:--------------------------------------|
| Identifiant (PID): <span style="font-size: 11px; margin-top: 5px;">(L’identifiant est attribué automatiquement par le dépôt lors de la mise en ligne).</span>  | <span class="overview-table-no">obligatoire</span>  | DC.Identifier   					  | Digital Object Identifier     		  |
|   | <span class="overview-table-no">obligatoire</span>  | DC.Date   							  | Publication date   |
|   | <span class="overview-table-no">obligatoire</span>  | DC.Title   		   					  | Title   |
|   | <span class="overview-table-no">obligatoire</span>  | DC.Creator   						  | Authors   |
|   | <span class="overview-table-yes">optionnel</span>   | DC.Contributeur 					  | Contributors    |
|   | <span class="overview-table-no">obligatoire</span>  | DC.Description  					  |  Description   |
|   | <span class="overview-table-yes">optionnel</span>   | DC.Format   						  |  _(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)_   |
|   | <span class="overview-table-yes">optionnel</span>   |   									  |  _(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)_   |
|   | <span class="overview-table-yes">optionnel</span>   |    									  |  _(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)_   |
|   | <span class="overview-table-yes">optionnel</span>   |    						   			  |  _(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)_   |
|   | <span class="overview-table-yes">optionnel</span>   |    									  |  _(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)_   |
|   | <span class="overview-table-yes">optionnel</span>   |    									  |  _(Incorporer ces informations dans le champ “Description” lors de la saisie des métadonnées)_   |
|   | <span class="overview-table-yes">optionnel</span>   |    									  |  Version   |
|   | <span class="overview-table-yes">optionnel</span>   | DC.Language   						  |  Language   |
|   | <span class="overview-table-yes">optionnel</span>   | DC.Subject   						  |  Keywords   |
|   | <span class="overview-table-yes">optionnel</span>   | DC.Rights   						  |  Access right & License   |
|   | <span class="overview-table-yes">optionnel</span>   |    									  |  Funding / Grants   |
|   | <span class="overview-table-yes">optionnel</span>   | DC.Relation   						  |  Related/alternate identifiers   |






*************


| Rubriques principales     | Correspondance éléments _Dublin Core_    |
:---------------------------|:--------------------------------------|
| Identifiant (PID):   | _DC.Identifier_  |
| Intitulé (des données): | _DC.Title_  |
| Auteur(s):   | _DC.Creator_  |
| Contributeur(s):   | _DC.Contributeur_  |
| Éditeur:<br/> _(par exemple équipe ou institution)_   | _DC.Publisher_  |
| Financement:    |   |
| Date de la publication (des données):    | _DC.Date_  |
| Dernière modification (des données):   |   |
| Version (des données):   |   |
| Propriétaire (des données):    |   |
| Langue(s):    | _DC.Language_  |
| Description (des données):   | _DC.Description_  |
| Mots-clés:    |  _DC.Subject_ |

| Rubriques complémentaires (selon principes FAIR)     | Correspondance éléments _Dublin Core_    |
:------------------------------------------------------|:--------------------------------------|
| Format de fichier (FAIR: I1):<br/> _(voir [Liste of file formats](https://en.wikipedia.org/wiki/List_of_file_formats){:target="_blank"})_   | _DC.Format_  |
| Logiciels nécessaires pour la lecture des données: (nom, version, système d’exploitation) (FAIR: I1):   |   |
| Si format ou logiciel particulier, expliquer clairement pourquoi ils ont été choisis (FAIR: I1):   |   |
| Si les données ne sont pas explicites en l’état, renvoyer vers les explications/documentation/vocabulaire pour expliciter les données (FAIR: I2):   |   |
| Licence des données (FAIR: R1.1):   |  _DC.Rights_ |
| Provenance et historique des données (FAIR R.1.2):   |   |
| Standards, conventions des données utilisées (FAIR: R1.3):   |   |
| Données liées (FAIR: I3):<br/> _(mentionner, le cas échéant, le PID, l’intitulé des données liées et le type de lien. Par exemple “ces textes (PID, intitulé du jeu de données avec les textes) <u>est la transcription</u> de ces photos de manuscrits (PID, intitulé du jeu de données avec les images)”_   |  _DC.Relation_ |

