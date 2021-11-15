---
layout: default
title: Vue d’ensemble
nav_order: 2
---

<style>
th, td {
  min-width: 103px;
  font-size: 11px !important;
}
</style>

# Vue d'ensemble

Le consortium COSME² soutient **29 corpus** différents développés au sein de **15 universités et institutions académiques françaises et étrangères**. Chaque corpus représente l’ensemble des informations issues des différentes sources de l’histoire médiévale. Le positionnement du consortium COSME2 est pluridisciplinaire et fait appel à une communauté scientifique largement ouverte à toutes les disciplines, de l’archéologie jusqu’à la philosophie.

Sur les 29 corpus, **16 possèdent un site internet personnel** et **11 sont ou seront hébergés par la plateforme TELMA** (4 corpus le sont déjà, 7 autres sont en cours de migration vers TELMA). Parmi les corpus présents sur internet, la totalité est hébergée sur des serveurs institutionnels (CNRS, Universités, Huma-Num).

## Données

Les données produites par les différents corpus du consortium COSME² appartiennent aux données des sciences humaines et sociales et plus précieusement aux données issues de l'histoire médiévale. Ceci explique la prédominance de certains types de données ou de certains formats et dicte le choix des standards appliqués aux données. 

En ce qui concerne les **types de données**, la majorité des **données sont textuelles**. Outre les données textuelles, plusieurs corpus possèdent également des **données visuelles** (photos des manuscrits, épigraphie, armoiries). Plusieurs corpus possèdent déjà, ou envisagent d’en avoir, des **données géographiques** (par exemple les géoréférencements des monastères).

Les **formats** les plus utilisés pour les données textuelles sont **xml** (pour les textes balisés) et **txt**, **doc** (pour les textes non balisés). Certains corpus ont mis en place différents modèles complexes de la représentation des données, notamment les bases de données relationnelles; la grande partie de ces bases s’appuie sur des données au format **sql**. Quelques projets font également appel aux tableurs (format **csv ou xlsx**). Enfin, toutes les données visuelles utilisent le format **jpg**. Les formats utilisés par les corpus du consortium sont donc assez répandus et, à quelques exceptions près, ils ne nécessitent pas de faire appel à des logiciels spécifiques pour la lecture des données.

Enfin, à l’heure actuelle il ne semble pas exister des conventions ou des **standards** largement admis pour encoder ou représenter sous une forme numérique différents types de données issues de l’histoire médiévale. On ne peut que signaler l’utilisation des **recommandations de TEI P5 ou EAD** pour l’encodage des données sous format xml.

Le tableau qui suit permet d'avoir un aperçu des informations principales sur chaque corpus et ses données et sur leur correspondance (simplifiée) aux principes FAIR. Pour plus de détails sur chaque corpus, voir: [Corpus](/docs/corpus){:target="_blank"}. Ces informations sont régulièrement mises à jour au fur et à mesure de l'avancement des opérations de la FAIRisation.

##### Corpus du consortium COSME² et leur correspondance aux principes FAIR (voir: [Corpus](/docs/corpus){:target="_blank"})
{: .text-center }

| Corpus       | Format(s)       	     | Taille 			       | Findable			     | Accessible 		     	 | Interoperable 	     	|  Reusable 	  |
|:-------------|:----------------------|:--------------------|:------------------|:----------------------|:---------------------|:--------------|
| Europange | pdf, jpg, sql  | 12 Go | <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-no">Non</span>|
| Transscript  | sql, jpg | quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Aposcripta  | sql | quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Armma  | sql, jpg| texte: 21 Mo; images: 17,2 Go | <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-no">Non</span>|
| Bullarium Franciscanum  | en cours de migration vers TELMA| quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Cartulaires italiens  | en cours de migration vers TELMA| quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span> | <span class="overview-table-no">Non</span>|
| Cartulaires walllons  | en cours de migration vers TELMA | quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| CartulR  | sql| quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Castellanie  | xml, jpg| ≈ 1Go| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| CBMA (Corpus Burgundiae Medii Aevi)  | fmp12, csv, tab, xlsx, xml, jpg, txt, pdf, doc/docx| ≈ 30-50 Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-no">Non</span>|
| CEMA (Cartae Europae Medii Aevi)   | xml, txt, csv, ods, sql| textes: 700 Mo; bibliographie: < 1 Mo; édition numérisé (3200 pdf): 198 Go| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| CIFM-CBMA (Corpus des Inscriptions de la France Médiévale) (Corpus Burgundiae Medii Aevi)  | csv (export de CBMA) > txt; xml (textes lemmatisés pour TXM)| ≈ 1 Mo | <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-no">Non</span>|
| Col&Mon (Collégiales et monastères de la réforme carolingienne au Concile de Trente)  | sql, jpg, png| 500 Ko (base Col&Mon); 15 Mo (base Collégiales) + 100 Mo images; 10 Mo (base Monastères) + 1 Go images| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-no">Non</span>|
| Comptabilités Principautés S/E  | xml, jpg| > 600 Mo |  <span class="overview-table-yes">Oui</span> |  <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span> |  <span class="overview-table-yes">Oui</span> |
| Devise  | sql, jpg| texte: 5,2 Mo; images: 116 Mo | <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Distinguo  | xml| ≈ 15 Mo | <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-no">Non</span>|
| e-Cartae  | xml, jpg| 2,74 Mo (266 fichiers)| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-no">Non</span>|
| Golubovic  | transformation en cours vers xml| quelques Mo | <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span> | <span class="overview-table-no">Non</span>|
| Lettres Jean XXII  | en cours de migration vers TELMA | quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Originaux 1&2  | sql | quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| PALM (Plateforme d'analyse linguistique médiévale)  | xml| 22 Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-no">Non</span>|
| Répertoire des anciens inventaires d'archives ecclésiastiques... |  xml (site AN); csv (migration vers TELMA)| 123 Ko|  <span class="overview-table-yes">Oui</span>|  <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span> |  <span class="overview-table-partially">Partiellement</span> |
| Ressources médiévistes  | doc| < 1 Mo| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| Scripta  | xml| moins de quelques Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-no">Non</span>|
| Scriptorium  | sql| 20,7 Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Sigilla  | sql, jpg| impossible à définir| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Studium parisiense  | documents json (MongoDB)| impossible à définir | <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Titulus  | xml, jpg| impossible à définir| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>|  <span class="overview-table-yes">Oui</span> | <span class="overview-table-no">Non</span>|
| Prosopange  | sql, pdf, json, geoJson| 62 Mo| <span class="overview-table-no">Non</span>| <span class="overview-table-no">Non</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|

