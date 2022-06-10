---
layout: default
title: Scriptorium
parent: Corpus
nav_order: 25
---

# Scriptorium / Bulletin codicologique
{: .no_toc }

## Table des matières
{: .no_toc .text-delta .text-grey-dk-100 }

1. TOC
{:toc}

---

### Information générale

| <span class="corpus-table-header-left">Nom du corpus</span>                           | Scriptorium / Bulletin codicologique |
| <span class="corpus-table-header-left">Adresse web</span>                             | [Scriptorium / Bulletin codicologique](http://www.scriptorium.be/catalogue.php){:target="_blank"} |
| <span class="corpus-table-header-left">Responsables scientifiques et techniques</span> | Van den Abeele, Baudouin (Centre International de Codicologie ASBL) : Project leader <br/> Smal, Antony (Centre International de Codicologie ASBL) : Project manager <br/> Lefèvre, Mickaël (Centre International de Codicologie ASBL) : Project manager (past)|

### Description des données

| <span class="corpus-table-header-left">Nature de données</span>                                            | données textuelles |
| <span class="corpus-table-header-left">Format de données</span>                                            | sql |
| <span class="corpus-table-header-left">Standards des données</span>                                        | modèle personnel (base de données SQL) |
| <span class="corpus-table-header-left">Taille des fichiers</span>                                          | 20,7 Mo |
| <span class="corpus-table-header-left">Unité de donnée et nb.d’unités</span>                               | 32.778 notices et références bibliographiques <br/> 281.087 cotes de manuscrit |
| <span class="corpus-table-header-left">Logiciels spécifiques nécessaires pour la lecture des données</span>| non |
| <span class="corpus-table-header-left">Plateforme d’affichage et de stockage des données</span>            | site dédié (hébergé par l'Institut de Recherche et d’Histoire des Textes) <br/> _Une migration des données vers une autre structure est prévue prochainement. La nouvelle version de Scriptorium est réalisée avec le pôle numérique de l’IRHT et utilisera la même plateforme que Bibale. Les données seront stockées dans une base de données SQL._ |

### Correspondance aux principes FAIR

#### Findable (= Facile à trouver)
{: .no_toc }

| F1: Les (méta)données possèdent un identifiant persistant et unique au monde (persistent identifier, PID)	  | <span class="overview-table-yes">Oui</span> |
| F2: Les données sont décrites avec des métadonnées riches													  | <span class="overview-table-yes">Oui</span> |
| F3: Les métadonnées incluent, d’une façon claire et explicite, l’identifiant des données qu’elles décrivent | <span class="overview-table-yes">Oui</span> |
| F4: Les (méta)données sont enregistrées ou indexées dans une ressource consultable						  | <span class="overview-table-yes">Oui</span> |

#### Accessible
{: .no_toc }

| A1. Les (méta)données sont récupérables par leur identifiant en utilisant un protocole standard de communication | <span class="overview-table-yes">Oui</span> |
| A1.1. Le protocole est ouvert, gratuit et largement utilisé													   | <span class="overview-table-yes">Oui</span> |
| A1.2. Le protocole permet, si nécessaire, une procédure d'authentification et d'autorisation					   | <span class="overview-table-yes">Oui</span> |
| A2. Les métadonnées sont accessibles, même lorsque les données ne sont plus disponibles						   | <span class="overview-table-yes">Oui</span> |

#### Interoperable (= Interopérable)
{: .no_toc }

| I1. Les (méta)données utilisent un langage formel, accessible, partagé et largement répandu pour la représentation des connaissances | <span class="overview-table-yes">Oui</span> |
| I2. Les (méta)données utilisent des vocabulaires qui suivent les principes FAIR 													   | <span class="overview-table-yes">Oui</span> |
| I3. Les (méta)données incluent des références qualifiées à d'autres (méta)données 												   | <span class="overview-table-yes">Oui</span> |

#### Reusable (= Réutilisable)
{: .no_toc }

| R1. Les méta(données) sont décrites d’une façon complète avec plusieurs attributs précis et pertinents	| <span class="overview-table-yes">Oui</span> |
| R1.1. Les (méta)données sont publiées avec une licence d'utilisation des données claire et accessible 	| <span class="overview-table-yes">Oui</span> |
| R1.2. Les (méta)données disposent d’une provenance détaillée												| <span class="overview-table-yes">Oui</span> |
| R1.3. Les (méta)données répondent aux standards communautaires de leur domaine							| <span class="overview-table-yes">Oui</span> |

### FAIRisation

| <span class="corpus-table-header-left">Données FAIRisées</span>        	 | _données textuelles:_ SQL (export depuis le site web [Scriptorium / Bulletin codicologique](http://www.scriptorium.be/catalogue.php){:target="_blank"}) |
| <span class="corpus-table-header-left">Dépôt de données</span>          	 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6603279.svg)](https://doi.org/10.5281/zenodo.6603279){:target="_blank"} |
| <span class="corpus-table-header-left">Citation bibliographique</span>  	 | Centre International de Codicologie ASBL. (2022). Scriptorium / Bulletin codicologique (1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.6603279 |
| <span class="corpus-table-header-left">Documentation technique</span>   	 | [MySQL Documentation](https://dev.mysql.com/doc/) <br/> La documentation supplémentaire est également incluse dans le dépôt Zenodo. |
| <span class="corpus-table-header-left">Infrastructure personnelle</span>   | non |