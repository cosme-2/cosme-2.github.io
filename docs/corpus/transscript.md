---
layout: default
title: Transscript
parent: Corpus
nav_order: 2
---

# Transscript
{: .no_toc }

## Table des matières
{: .no_toc .text-delta .text-grey-dk-100 }

1. TOC
{:toc}

---

### Information générale

| <span class="corpus-table-header-left">Nom du corpus</span>                           | Transscript |
| <span class="corpus-table-header-left">Adresse web</span>                             | [TELMA: Transscript](http://telma-chartes.irht.cnrs.fr/transscript/page/transscript-project){:target="_blank"} |
| <span class="corpus-table-header-left">Resposables scientifiques et techniques</span> | Isabelle Guyot-Bachy (Université de Lorraine); <br/>Michel Margue (Université de Luxembourg) |

### Description des données

| <span class="corpus-table-header-left">Nature de données</span>                                            | données textuelles, données visuelles (photos des manuscrits) |
| <span class="corpus-table-header-left">Format de données</span>                                            | sql (certains éléments textuels peuvent garder les traces du balisage XML); <br/>jpg |
| <span class="corpus-table-header-left">Standards des données</span>                                        | modèle personnel (base de données MySQL de TELMA) |
| <span class="corpus-table-header-left">Taille des fichiers</span>                                          | impossible à définir |
| <span class="corpus-table-header-left">Unité de donnée et nb.d’unités</span>                               | 900 textes |
| <span class="corpus-table-header-left">Logiciels spécifiques nécessaires pour la lecture des données</span>| non |
| <span class="corpus-table-header-left">Plateforme d’affichage et de stockage des données</span>            | TELMA Chartes<sup>*</sup> |

__\*__ - À l’heure actuelle, la plateforme TELMA se décline en deux sous-entités: [TELMA Chartes](http://telma-chartes.irht.cnrs.fr/){:target="_blank"} et [TELMA Repertoires](https://telma-repertoires.irht.cnrs.fr){:target="_blank"}. La migration vers [l’adresse unique](http://telma.irht.cnrs.fr){:target="_blank"} est prévue prochainement.
{: .lh-1 .fs-2 .text-grey-dk-100 }

### Correspondance aux principes FAIR

#### Findable (= Facile à trouver)
{: .no_toc }

| F1: Les (méta)données possèdent un identifiant persistant et unique au monde (persistent identifier, PID)	  | <span class="overview-table-no">Non</span> |
| F2: Les données sont décrites avec des métadonnées riches													  | <span class="overview-table-no">Non</span> |
| F3: Les métadonnées incluent, d’une façon claire et explicite, l’identifiant des données qu’elles décrivent | <span class="overview-table-no">Non</span> |
| F4: Les (méta)données sont enregistrées ou indexées dans une ressource consultable						  | <span class="overview-table-no">Non</span> |

#### Accessible
{: .no_toc }

| A1. Les (méta)données sont récupérables par leur identifiant en utilisant un protocole standard de communication | <span class="overview-table-no">Non</span> |
| A1.1. Le protocole est ouvert, gratuit et largement utilisé													   | <span class="overview-table-no">Non</span> |
| A1.2. Le protocole permet, si nécessaire, une procédure d'authentification et d'autorisation					   | <span class="overview-table-no">Non</span> |
| A2. Les métadonnées sont accessibles, même lorsque les données ne sont plus disponibles						   | <span class="overview-table-no">Non</span> |

#### Interoperable (= Interopérable)
{: .no_toc }

| I1. Les (méta)données utilisent un langage formel, accessible, partagé et largement répandu pour la représentation des connaissances | <span class="overview-table-yes">Oui</span> |
| I2. Les (méta)données utilisent des vocabulaires qui suivent les principes FAIR 													   | <span class="overview-table-partially">Partiellement</span> |
| I3. Les (méta)données incluent des références qualifiées à d'autres (méta)données 												   | <span class="overview-table-no">Non</span> |

#### Reusable (= Réutilisable)
{: .no_toc }

| R1. Les méta(données) sont décrites d’une façon complète avec plusieurs attributs précis et pertinents	| <span class="overview-table-no">Non</span> |
| R1.1. Les (méta)données sont publiées avec une licence d'utilisation des données claire et accessible 	| <span class="overview-table-no">Non</span> |
| R1.2. Les (méta)données disposent d’une provenance détaillée												| <span class="overview-table-no">Non</span> |
| R1.3. Les (méta)données répondent aux standards communautaires de leur domaine							| <span class="overview-table-no">Non</span> |

### FAIRisation

| <span class="corpus-table-header-left">Données FAIRisées</span>         | _données textuelles:_ JSON (export depuis TELMA)<br/>_données visuelles:_ JPG |
| <span class="corpus-table-header-left">Dépôt de données</span>         	 | _en cours_ |
| <span class="corpus-table-header-left">Citation bibliographique</span>  	 | _en cours_ |
| <span class="corpus-table-header-left">Documentation technique</span>   	 | [Schema JSON"](https://github.com/cosme-2/corpus/tree/main/transscript){:target="_blank"} |
| <span class="corpus-table-header-left">Infrastructure personnelle</span>   | non |