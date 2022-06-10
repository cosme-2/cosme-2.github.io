---
layout: default
title: Devise
parent: Corpus
nav_order: 15
---

# Devise
{: .no_toc }

## Table des matières
{: .no_toc .text-delta .text-grey-dk-100 }

1. TOC
{:toc}

---

### Information générale

| <span class="corpus-table-header-left">Nom du corpus</span>                           | Devise|
| <span class="corpus-table-header-left">Adresse web</span>                             | [Devise](https://devise.saprat.fr/page/la-base-devise){:target="_blank"} |
| <span class="corpus-table-header-left">Responsables scientifiques et techniques</span> | Laurent Hablot (EPHE) |

### Description des données

| <span class="corpus-table-header-left">Nature de données</span>                                            | données textuelles, données visuelles |
| <span class="corpus-table-header-left">Format de données</span>                                            | sql, jpg |
| <span class="corpus-table-header-left">Standards des données</span>                                        | modèle personnel |
| <span class="corpus-table-header-left">Taille des fichiers</span>                                          | texte (sql): 5,2 Mo <br/> images (jpg): 116 Mo |
| <span class="corpus-table-header-left">Unité de donnée et nb.d’unités</span>                               | 1000 notices |
| <span class="corpus-table-header-left">Logiciels spécifiques nécessaires pour la lecture des données</span>| non |
| <span class="corpus-table-header-left">Plateforme d’affichage et de stockage des données</span>            | Affichage: site dédié <br/> Stockage des donnée: en cours de migration vers Nakala. |

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

| <span class="corpus-table-header-left">Données FAIRisées</span>        	 | _données textuelles:_ SQL (export depuis le site web [Devise](https://devise.saprat.fr/page/la-base-devise){:target="_blank"}) |
| <span class="corpus-table-header-left">Dépôt de données</span>          	 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6631802.svg)](https://doi.org/10.5281/zenodo.6631802){:target="_blank"} |
| <span class="corpus-table-header-left">Citation bibliographique</span>  	 | Hablot, Laurent. (2022). DEVISE [Data set]. Zenodo. https://doi.org/10.5281/zenodo.6631802 |
| <span class="corpus-table-header-left">Documentation technique</span>   	 | [MySQL Documentation](https://dev.mysql.com/doc/){:target="_blank"} <br/> La documentation supplémentaire est également incluse dans le dépôt Zenodo. |
| <span class="corpus-table-header-left">Infrastructure personnelle</span>   | non |
