---
layout: default
title: Annexe 8. Exemple de la FAIRisation
parent: Guide FAIR
nav_order: 11
---

# Annexe 8. Exemple de la FAIRisation par l’intermédiaire du versement des données dans un dépôt
{: .no_toc }

**Rappel:** L’exemple de la FAIRisation qui suit se base entièrement sur le programme de la FAIRisation proposé plus haut (voir _supra_ ["Étapes de la FAIRisation"](/docs/fair-guide/fairization){:target="_blank"}). Chaque étape de la FAIRisation a été appliquée au corpus [“Comptabilités Principautés S/E”](https://cosme-2.github.io/docs/corpus/ressourcescomptables.html). Le dépôt retenu pour le versement des données est Zenodo (administré par le CERN et soutenu par la Commission européenne et les programmes Horizon 2020 et OpenAIRE). (Sur le choix d’un dépôt voir _supra_ [Annexe 3](/docs/fair-guide/annexe-3){:target="_blank"} et [Annexe 2](/docs/fair-guide/annexe-2){:target="_blank"}).
{: .fw-300 }

À noter cependant qu’il s’agit de la FAIRisation “allégée”. De fait, le corpus “Comptabilités Principautés S/E” contient aussi bien les textes que les images; la FAIRisation qui suit ne s’applique qu’aux textes. On retient également que dans l’hypothèse du versement des données dans un dépôt institutionnel, la partie “métadonnées” des principes FAIR est garantie avant tout par le dépôt. Dans cette optique, l’auteur des données garantit essentiellement les principes FAIR liés aux données (voir _supra_ [“Qui FAIRise quoi?”](/docs/fair-guide/presentation.html#qui-fairise-quoi){:target="_blank"} et les [Annexe 1](/docs/fair-guide/annexe-1){:target="_blank"} et [Annexe 2](/docs/fair-guide/annexe-2){:target="_blank"}).
{: .fw-300 }

Le dépôt Zenodo possède le mécanisme de la gestion des versions (le versioning), ce qui permet, par la suite, de corriger, d’ajouter et de modifier les données au fur et à mesure. À noter toutefois que la mise à jour du dépôt passe ne pas par la correction des fichiers déjà déposés, mais par la création d’une nouvelle version avec son propre identifiant (DOI). Le jeu de données déposé possédera également un identifiant (DOI) “global” qui regroupe toutes les versions. Sur le versioning dans le dépôt Zenodo voir: [Zenodo - DOI versioning](https://help.zenodo.org/#versioning).
{: .fw-300 }

**Pour le dépôt qui résulte de cette FAIRisation voir: [Ressources comptables en Dauphiné, Provence, Savoie et Venaissin (XIII<sup>e</sup> - XV<sup>e</sup> siècle)](https://zenodo.org/record/4919334).**
{: .fw-300 }

Pour d’autres exemples des dépôts des corpus médiévaux, voir:
{: .fw-300 }

- He, Sheng, Schomaker, Lambert, Samara, Petros, & Burgers, Jan. (2016). MPS Data set with images of medieval charters for handwriting-style based dating of manuscripts (Version v1.0) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.1194357  
- Koho, Mikko, Tuominen, Jouni, Lewis, David, Ikkala, Esko, Heller, Benjamin, Thomson, Emma, … Fraas, Mitch. (2021). Mapping Manuscript Migrations Knowledge Graph (Version 2.2.0) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.4440464 
- Silvia Corbara, Alejandro Moreo, Fabrizio Sebastiani, & Mirko Tavoni. (2020). Two Datasets for the Computational Authorship Analysis of Medieval Latin Texts (Version 2.00) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.4298503 
{: .fw-300 }

---

Présentation des données
(voir fiche détaillée du corpus “Comptabilités Principautés S / E”)

Corpus: Comptabilités Principautés S / E 
Format des données: XML (texte)
Standard des données: XML TEI P5
Unité de données: 25 comptes (=25 fichiers XML)
Affichage et stockage des données: les données sont affichées sur un site web personnel, mais sont stockées et interrogées via la base eXist-db.


FAIRisation des données
(voir supra le programme complet et toutes les étapes de la FAIRisation “2. Étapes de la FAIRisation”)

1. Vérification des données

1.1. S’assurer que les langages et les formats/extensions utilisés pour l’encodage des données sont connus, largement utilisés et, de préférence, libres.
XML est un format connu et largement utilisé.
FAIR: I1 - rempli

1.2. S’assurer que les données sont explicites et compréhensibles en l’état. Cela signifie que toutes les abréviations, tous les termes ambigus ou toutes les balises utilisées dans la description des données doivent être clairement expliqués ou avoir déjà une documentation existante. 
XML TEI P5 est un standard connu qui possède une documentation.
FAIR: I2 - rempli

1.3. Créer un jeu de données du corpus. (Le plus souvent c’est un seul fichier de l’archive numérique, par exemple sous format zip).
On crée un fichier de l’archive numérique zip de tous les fichiers XML.













************************






**Rappel:** Il est utile de rappeler que les principes FAIR ne sont que des recommandations qui visent à rendre les données scientifiques plus accessibles et plus compréhensibles et leurs sauvegarde et réutilisation plus pérennes. La _FAIRititude_ [FAIRness] complète des données n’est cependant qu’un objectif théorique difficilement atteignable (sur ce point, voir la bibliographie [[2](/docs/fair-guide/bibliography#2){:target="_blank"}], [[3](/docs/fair-guide/bibliography#3){:target="_blank"}], [[10](/docs/fair-guide/bibliography#10){:target="_blank"}], [[12](/docs/fair-guide/bibliography#12){:target="_blank"}]). Par conséquent, chaque champ des métadonnées doit être rempli le plus complètement possible, mais dans des limites raisonnables.
{: .fw-300 }

<details open markdown="block">
  <summary>
    Table des matières
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## FAIR par la pratique




