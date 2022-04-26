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
{: .no_toc }

<details open markdown="block">
  <summary>
    Table des matières
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

Le consortium COSME² soutient **29 corpus** différents développés au sein de **15 universités et institutions académiques françaises et étrangères**. Chaque corpus représente l’ensemble des informations issues des différentes sources de l’histoire médiévale. Le positionnement du consortium COSME2 est pluridisciplinaire et fait appel à une communauté scientifique largement ouverte à toutes les disciplines, de l’archéologie jusqu’à la philosophie.

Sur les 29 corpus, **16 possèdent un site internet personnel** et **11 sont ou seront hébergés par la plateforme TELMA** (4 corpus le sont déjà, 7 autres sont en cours de migration vers TELMA). Parmi les corpus présents sur internet, la totalité est hébergée sur des serveurs institutionnels (CNRS, Universités, Huma-Num).

## Données des corpus

Les données produites par les différents corpus du consortium COSME² appartiennent aux données des sciences humaines et sociales et plus précieusement aux données issues de l'histoire médiévale. Ceci explique la prédominance de certains types de données ou de certains formats et dicte le choix des standards appliqués aux données. 

En ce qui concerne les **types de données**, la majorité des **données sont textuelles**. Outre les données textuelles, plusieurs corpus possèdent également des **données visuelles** (photos des manuscrits, épigraphie, armoiries). Plusieurs corpus possèdent déjà, ou envisagent d’en avoir, des **données géographiques** (par exemple les géoréférencements des monastères).

Les **formats** les plus utilisés pour les données textuelles sont **xml** (pour les textes balisés) et **txt**, **doc** (pour les textes non balisés). Certains corpus ont mis en place différents modèles complexes de la représentation des données, notamment les bases de données relationnelles; la grande partie de ces bases s’appuie sur des données au format **sql**. Quelques projets font également appel aux tableurs (format **csv ou xlsx**). Enfin, toutes les données visuelles utilisent le format **jpg**. Les formats utilisés par les corpus du consortium sont donc assez répandus et, à quelques exceptions près, ils ne nécessitent pas de faire appel à des logiciels spécifiques pour la lecture des données.

Enfin, à l’heure actuelle il ne semble pas exister des conventions ou des **standards** largement admis pour encoder ou représenter sous une forme numérique différents types de données issues de l’histoire médiévale. On ne peut que signaler l’utilisation des **recommandations de TEI P5 ou EAD** pour l’encodage des données sous format xml.

Les objectifs et moyens divers de chaque corpus peuvent en outre dicter des démarches variées dans la mise en pratique des principes FAIR. En définitive, il est possible d’envisager deux approches: la mise des données dans un dépôt de données institutionnel ou l’élaboration d’une infrastructure personnelle de gestion des données. (Pour plus de détails, voir ["Écosystème FAIR"](/docs/fair-guide/presentation.html#écosystème-fair){:target="_blank"}).

## Tableau récapitulatif des corpus et leur correspondance aux principes FAIR

Le tableau qui suit permet d'avoir un aperçu des informations principales sur chaque corpus et ses données et sur leur correspondance (simplifiée) aux principes FAIR. Pour plus de détails sur chaque corpus, voir: [Corpus](/docs/corpus){:target="_blank"}. Ces informations sont mises à jour au fur et à mesure de l'avancement des opérations de la FAIRisation.

##### Corpus du consortium COSME² et leur correspondance aux principes FAIR (voir: [Corpus](/docs/corpus){:target="_blank"})
{: .no_toc .text-center }

_<u>(glissez ou déroulez le tableau à gauche et à droite pour le voir en entier)</u>_
{: .fs-3 .text-center }

<span class="fs-3">
[Télécharger le tableau récapitulatif en version PDF](/assets/doc/Guide-FAIR-v.3.2-[04.01.2022]-COSME2.pdf){: .btn .btn-blue .fw-300 .text-grey-lt-000  .d-inline-block .float-left }
</span>

| Corpus       | Format(s)       	     | Taille 			       | Écosystème FAIR     | Findable			     | Accessible 		     	 | Interoperable 	     	|  Reusable 	  |
|:-------------|:----------------------|:--------------------|:--------------------|:------------------|:----------------------|:---------------------|:--------------|
| Europange | pdf, jpg, sql  | 12 Go | infrastructure personnelle, Isidore  | <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>|
| Transscript  | sql, jpg | quelques Mo| Non FAIRisé<sup style="font-size: 12px !important; font-weight: bold;">*</sup> | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| Aposcripta  | sql | quelques Mo| _à venir_ | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| Armma  | sql, jpg| texte: 21 Mo; images: 17,2 Go | _à venir_ | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-no">Non</span>|
| Bullarium Franciscanum  | sql (TELMA), json (Zenodo) | quelques Mo| dépôt de données (Zenodo) | <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| Cartulaires italiens  | en cours de création sur TELMA| quelques Mo| _Les données ne sont pas prêtes pour la FAIRisation_ | _Les données ne sont pas prêtes pour la FAIRisation_ | _Les données ne sont pas prêtes pour la FAIRisation_ | _Les données ne sont pas prêtes pour la FAIRisation_ | _Les données ne sont pas prêtes pour la FAIRisation_ |
| Cartulaires walllons  | sql (TELMA), json (Zenodo) | quelques Mo| dépôt de données (Zenodo) | <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| CartulR  | sql (TELMA), json (Zenodo)| quelques Mo| dépôt de données (Zenodo) | <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| Castellanie  | xml, jpg| ≈ 1Go| _à venir_ | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| CBMA (Corpus Burgundiae Medii Aevi)  | fmp12, csv, tab, xlsx, xml, jpg, txt, pdf, doc/docx| ≈ 30-50 Mo| dépôt de données (Nakala) | <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| CEMA (Cartae Europae Medii Aevi)   | xml, txt, csv, ods, sql, pdf| textes: 700 Mo; bibliographie: < 1 Mo; édition numérisé (3200 pdf): 198 Go| en cours de création du jeu de données | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| CIFM-CBMA (Corpus des Inscriptions de la France Médiévale) (Corpus Burgundiae Medii Aevi)  | csv (export de CBMA) > txt; xml (textes lemmatisés pour TXM)| ≈ 1 Mo | dépôt de données (Nakala) | <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| Col&Mon (Collégiales et monastères de la réforme carolingienne au Concile de Trente)  | sql, jpg, png| 500 Ko (base Col&Mon); 15 Mo (base Collégiales) + 100 Mo images; 10 Mo (base Monastères) + 1 Go images| _à venir_ | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| Comptabilités Principautés S/E  | xml, jpg| > 600 Mo | dépôt de données (Zenodo) | <span class="overview-table-yes">Oui</span> |  <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span> |  <span class="overview-table-yes">Oui</span> |
| Devise  | sql, jpg| texte: 5,2 Mo; images: 116 Mo | _à venir_ | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Distinguo  | xml| ≈ 15 Mo | _à venir_ | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| e-Cartae  | xml, jpg| 2,74 Mo (266 fichiers)| _à venir_ | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| Golubovic  | transformation en cours vers xml| quelques Mo | _Les données ne sont pas prêtes pour la FAIRisation_ | _Les données ne sont pas prêtes pour la FAIRisation_ | _Les données ne sont pas prêtes pour la FAIRisation_ | _Les données ne sont pas prêtes pour la FAIRisation_ | _Les données ne sont pas prêtes pour la FAIRisation_ |
| Lettres Jean XXII  | sql (TELMA), json (Zenodo) | < 3 Mo| dépôt de données (Zenodo) |  <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| Originaux 1&2  | sql | quelques Mo| Non FAIRisé<sup style="font-size: 12px !important; font-weight: bold;">*</sup> | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| PALM (Plateforme d'analyse linguistique médiévale)  | xml| 22 Mo| _à venir_ |  <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| Répertoire des anciens inventaires d'archives ecclésiastiques... |  xml (site AN, Zenodo); csv (migration vers TELMA)| 123 Ko| infrastructure personnelle (salle des inventaires virtuelle des AN); dépôt de données (Zenodo) |  <span class="overview-table-yes">Oui</span>|  <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span> |  <span class="overview-table-partially">Partiellement</span> |
| Ressources médiévistes  | sql (Heurist), csv (Zenodo) | < 1 Mo| dépôt de données (Zenodo) |  <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| Scripta  | xml| 65.4 Mo| dépôt de données (Zenodo) |  <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| Scriptorium  | sql| 20,7 Mo| _à venir_ |  <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Sigilla  | sql, jpg (Drupal), csv (Zenodo)| quelques Mo| dépôt de données (Zenodo) |  <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span>| <span class="overview-table-yes">Oui</span> | <span class="overview-table-yes">Oui</span>|
| Studium parisiense  | documents json (MongoDB)| impossible à définir | _à venir_ |  <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|
| Titulus  | xml, jpg| impossible à définir| _à venir_ |  <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>|  <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-partially">Partiellement</span>|
| Prosopange  | sql, pdf, json, geoJson| 62 Mo| _à venir_ |  <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span>| <span class="overview-table-partially">Partiellement</span> | <span class="overview-table-no">Non</span>|

 __\*__ - En l’absence d’un accord explicite de(s) auteur(s) du corpus, les données n’ont pas pu être FAIRisées.
{: .lh-1 .fs-2 .text-grey-dk-100 }

