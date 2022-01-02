---
layout: default
title: Annexe 8. Exemple de la FAIRisation
parent: Guide FAIR
nav_order: 11
---

# Annexe 8. Exemple de la FAIRisation par l’intermédiaire du versement des données dans un dépôt
{: .no_toc }

**Rappel:** L’exemple de la FAIRisation qui suit se base entièrement sur le programme de la FAIRisation proposé plus haut (voir _supra_ ["Étapes de la FAIRisation"](/docs/fair-guide/fairization){:target="_blank"}). Chaque étape de la FAIRisation a été appliquée au corpus [“Comptabilités Principautés S/E”](https://cosme-2.github.io/docs/corpus/ressourcescomptables.html){:target="_blank"}. Le dépôt retenu pour le versement des données est Zenodo (administré par le CERN et soutenu par la Commission européenne et les programmes Horizon 2020 et OpenAIRE). (Sur le choix d’un dépôt voir _supra_ [Annexe 3](/docs/fair-guide/annexe-3){:target="_blank"} et [Annexe 2](/docs/fair-guide/annexe-2){:target="_blank"}).
{: .fw-300 }

À noter cependant qu’il s’agit de la FAIRisation “allégée”. De fait, le corpus “Comptabilités Principautés S/E” contient aussi bien les textes que les images; la FAIRisation qui suit ne s’applique qu’aux textes. On retient également que dans l’hypothèse du versement des données dans un dépôt institutionnel, la partie “métadonnées” des principes FAIR est garantie avant tout par le dépôt. Dans cette optique, l’auteur des données garantit essentiellement les principes FAIR liés aux données (voir _supra_ [“Qui FAIRise quoi?”](/docs/fair-guide/presentation.html#qui-fairise-quoi){:target="_blank"} et les [Annexe 1](/docs/fair-guide/annexe-1){:target="_blank"} et [Annexe 2](/docs/fair-guide/annexe-2){:target="_blank"}).
{: .fw-300 }

Le dépôt Zenodo possède le mécanisme de la gestion des versions (le versioning), ce qui permet, par la suite, de corriger, d’ajouter et de modifier les données au fur et à mesure. À noter toutefois que la mise à jour du dépôt passe ne pas par la correction des fichiers déjà déposés, mais par la création d’une nouvelle version avec son propre identifiant (DOI). Le jeu de données déposé possédera également un identifiant (DOI) “global” qui regroupe toutes les versions. Sur le versioning dans le dépôt Zenodo voir: [Zenodo - DOI versioning](https://help.zenodo.org/#versioning){:target="_blank"}.
{: .fw-300 }

**Pour le dépôt qui résulte de cette FAIRisation voir: [https://zenodo.org/record/4919334](https://zenodo.org/record/4919334){:target="_blank"}.**
{: .fw-300 }

Pour d’autres exemples des dépôts des corpus médiévaux, voir:
{: .fw-300 }

- He, Sheng, Schomaker, Lambert, Samara, Petros, & Burgers, Jan. (2016). MPS Data set with images of medieval charters for handwriting-style based dating of manuscripts (Version v1.0) [Data set]. Zenodo. [http://doi.org/10.5281/zenodo.1194357](http://doi.org/10.5281/zenodo.1194357){:target="_blank"}  
- Koho, Mikko, Tuominen, Jouni, Lewis, David, Ikkala, Esko, Heller, Benjamin, Thomson, Emma, … Fraas, Mitch. (2021). Mapping Manuscript Migrations Knowledge Graph (Version 2.2.0) [Data set]. Zenodo. [http://doi.org/10.5281/zenodo.4440464](http://doi.org/10.5281/zenodo.4440464){:target="_blank"}
- Silvia Corbara, Alejandro Moreo, Fabrizio Sebastiani, & Mirko Tavoni. (2020). Two Datasets for the Computational Authorship Analysis of Medieval Latin Texts (Version 2.00) [Data set]. Zenodo. [http://doi.org/10.5281/zenodo.4298503](http://doi.org/10.5281/zenodo.4298503){:target="_blank"}
{: .fw-300 }

---

<details open markdown="block">
  <summary>
    Table des matières
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Présentation des données
_(voir fiche détaillée du corpus [“Comptabilités Principautés S/E”](/docs/corpus/ressourcescomptables){:target="_blank"})_
{: .fs-3 .fw-300 .lh-tight }

**Corpus:** Comptabilités Principautés S/E<br/>
**Format des données:** XML (texte)<br/>
**Standard des données:** XML TEI P5<br/>
**Unité de données:** 25 comptes (=25 fichiers XML)<br/>
**Affichage et stockage des données:** les données sont affichées sur un site web personnel, mais sont stockées et interrogées via la base eXist-db.

---

## FAIRisation des données
_(voir supra le programme complet et toutes les étapes de la FAIRisation [“Étapes de la FAIRisation”](/docs/fair-guide/fairization){:target="_blank"})_
{: .fs-3 .fw-300 .lh-tight }

### 1. Vérification des données
{: .mb-3 }

1.1. S’assurer que les langages et les formats/extensions utilisés pour l’encodage des données sont connus, largement utilisés et, de préférence, libres.
<span class="left-indent-bold">XML est un format connu et largement utilisé.</span>
<span class="left-indent-bold">FAIR: I1 - rempli.</span>

1.2. S’assurer que les données sont explicites et compréhensibles en l’état. Cela signifie que toutes les abréviations, tous les termes ambigus ou toutes les balises utilisées dans la description des données doivent être clairement expliqués ou avoir déjà une documentation existante.
<span class="left-indent-bold">XML TEI P5 est un standard connu qui possède une documentation.</span>
<span class="left-indent-bold">FAIR: I2 - rempli.</span>

1.3. Créer un jeu de données du corpus. (_Le plus souvent c’est un seul fichier de l’archive numérique, par exemple sous format zip_).
<span class="left-indent-bold">On crée un fichier de l’archive numérique zip de tous les fichiers XML.</span>

### 2. Préparation des métadonnées
{: .mb-3 }

2.1. Préparation des métadonnées complètes.

2.1.1. S’assurer que les métadonnées contiennent le plus de détails possible. (_Se référer au modèle des métadonnées détaillées, voir [Annexe 4](/docs/fair-guide/annexe-4){:target="_blank"}_)
<span class="left-indent-bold">Il n’existe aucune métadonnée pour le jeu de données du corpus. On écrit (pour l’instant dans n’importe quel fichier texte) les métadonnées en se basant sur le modèle de l’[Annexe 4](/docs/fair-guide/annexe-4){:target="_blank"}. Ces métadonnées seront par la suite utilisées lors de la mise des données dans un dépôt.</span> 
<span class="left-indent-bold">FAIR: F2 - en attente.</span>
{: .ml-6 }

2.1.2. S’assurer que les données disposent une licence et qu’elle est clairement mentionnée dans les métadonnées. (_Les données peuvent avoir tous types de licence, y compris les licences “non libres de droits”_). 
<span class="left-indent-bold">Si cela n’a pas été encore fait, on ajoute les informations sur la licence dans le brouillon des métadonnées créées précédemment.</span>
<span class="left-indent-bold">Licence des données (corpus “Comptabilités Principautés S/E”): Open Access (Creative Commons Attribution 4.0 International).</span>
<span class="left-indent-bold">FAIR: R1.1 - en attente.</span>
{: .ml-6 }

2.1.3. S’assurer que les métadonnées contiennent un historique détaillé de la provenance des données. (_Par exemple, les données peuvent être produites durant un autre projet et ensuite réutilisées, corrigées et modifiées par le présent projet_). 
<span class="left-indent-bold">Si cela n’a pas été encore fait, on ajoute les informations sur la provenance des données dans le brouillon des métadonnées créées précédemment.</span>
<span class="left-indent-bold">FAIR: R1.2 - en attente.</span>
{: .ml-6 }

2.1.4. S’assurer que les données utilisent des standards (s’il en existe) de présentation, d’organisation ou d’archivage communément utilisés dans le domaine scientifique auquel ces données appartiennent. (_Ces informations seront par la suite utilisées dans les métadonnées_).
<span class="left-indent-bold">Si cela n’a pas été encore fait, on ajoute les informations sur les standards dans le brouillon des métadonnées créées précédemment.</span>
<span class="left-indent-bold">Standards, conventions des données utilisées (corpus “Comptabilités Principautés S/E”): XML TEI P5.</span>
<span class="left-indent-bold">FAIR: R1.3 - en attente.</span>
{: .ml-6 }

2.2. S’assurer que dans les cas où les présentes données peuvent être reliées à d’autres données (par exemple, les données textuelles peuvent être reliées aux images des manuscrits), les métadonnées contiennent des références à ces données reliées (par exemple le PID des données reliées, voir F1). Le type de lien entre les données doit être explicitement mentionné. (Par exemple, “ce texte <u>est la transcription</u> de ce manuscrit” ou “ce texte <u>a été écrit</u> par cette personne”).
<span class="left-indent-bold">Si cela n’a pas été encore fait, on ajoute les informations sur les données liées dans le brouillon des métadonnées créées précédemment.</span>
<span class="left-indent-bold">FAIR: I3. - en attente.</span>

### 3. Mise des données dans un dépôt
{: .mb-3 }

3.1. Enregistrement des données et des métadonnées.

3.1.1. Choisir une ressource consultable (par exemple, un dépôt de données) qui répond à tous les critères FAIR applicables aux métadonnées (F1, F3, F4, A1.1, A1.2, A2, I1, I2, I3, R1.1, R1.2, R1.3). La plupart des grands dépôts de données affichent de façon claire leur conformité aux critères FAIR. (_Pour plus de détails sur le choix de dépôt et sur les critères FAIR auxquels il doit répondre voir infra [Annexe 3](/docs/fair-guide/annexe-3){:target="_blank"}_)
<span class="left-indent-bold">On choisit le dépôt Zenodo. Ce dépôt de données est une infrastructure officielle hébergée par le CERN et financée par l’European Commission (OpenAIRE & Horizon 2020). Ce dépôt répond à tous les critères FAIR, voir [Zenodo-FAIR Principles](https://about.zenodo.org/principles/){:target="_blank"}.</span>
{: .ml-6 }

3.1.2. Enregistrer les données et les métadonnées y associées dans une ressource consultable choisie précédemment. 
<span class="left-indent-bold">On enregistre les données et les métadonnées dans le dépôt Zenodo.</span>
<span class="left-indent-bold">FAIR: F4 - rempli.</span>
<span class="left-indent-bold">FAIR: F2 - rempli.</span>
<span class="left-indent-bold">FAIR: R1.1 - rempli.</span>
<span class="left-indent-bold">FAIR: R1.2 - rempli.</span>
<span class="left-indent-bold">FAIR: R1.3 - rempli.</span>
<span class="left-indent-bold">FAIR: I3. - rempli.</span>
{: .ml-6 }

![](/assets/images/Annexe8-Img1-Upload.jpg){:width="90%" .d-block .mx-auto}

![](/assets/images/Annexe8-Img2-Upload-with-file.jpg){:width="90%" .d-block .mx-auto}

##### Image 1 & 2. Ajouter le jeu de données.
{: .no_toc .text-center .mb-5 }

![](/assets/images/Annexe8-Img3-Dataset.jpg){:width="90%" .d-block .mx-auto}

![](/assets/images/Annexe8-Img4-Basic-information-1.jpg){:width="90%" .d-block .mx-auto}

![](/assets/images/Annexe8-Img5-Basic-information-2.jpg){:width="90%" .d-block .mx-auto}

![](/assets/images/Annexe8-Img6-Licence.jpg){:width="90%" .d-block .mx-auto}

![](/assets/images/Annexe8-Img7-Funding.jpg){:width="90%" .d-block .mx-auto}

![](/assets/images/Annexe8-Img8-Contributors.jpg){:width="90%" .d-block .mx-auto}

##### Image 3 & 8. Remplir le formulaire des métadonnées.
{: .no_toc .text-center .mb-5 }

![](/assets/images/Annexe8-Img9-Start-upload.jpg){: .d-block .mx-auto}

##### Image 9. Uploader le fichier du corpus.
{: .no_toc .text-center .mb-5 }

![](/assets/images/Annexe8-Img10-Publish.jpg){: .d-block .mx-auto}

##### Image 10. Publier le dépôt en ligne.
{: .no_toc .text-center .mb-5 }

**Le dépôt est en ligne: [https://zenodo.org/record/4919334](https://zenodo.org/record/4919334){:target="_blank"}**

3.2. Vérification de l’accessibilité et de l’exactitude des (méta)données.

3.2.1. Vérifier que les données possèdent un identifiant persistant et unique (PID) (fourni par la ressource où les données sont enregistrées). 
<span class="left-indent-bold">Le jeu de données possède l’identifiant DOI (“global”): 
[http://doi.org/10.5281/zenodo.4919334](http://doi.org/10.5281/zenodo.4919334){:target="_blank"} </span>
<span class="left-indent-bold">FAIR: F1 - rempli.</span>
{: .ml-6 }

3.2.2. Vérifier que le PID des données est mentionné dans les métadonnées.
<span class="left-indent-bold">Sur la page du dépôt on choisir Export, par exemple JSON:</span>
{: .ml-6 }

![](/assets/images/Annexe8-Img11-Metadata-Export.jpg){:width="80%" .d-block .mx-auto}

##### Image 11. Sélection de fichier d'export des métadonnées.
{: .no_toc .text-center .mb-5 }

<span class="left-indent-bold">Dans le texte qui s’affiche, on trouve l’identifiant:</span>
{: .ml-6 }

![](/assets/images/Annexe8-Img12-Metadata-DOI.jpg){:width="80%" .d-block .mx-auto}

##### Image 12. Le PID des données est mentionnées dans les métadonnées.
{: .no_toc .text-center .mb-5 }

<span class="left-indent-bold">FAIR: F3 - rempli.</span>
{: .ml-6 }

3.2.3. Vérifier que les données sont accessibles via un protocole de communication ouvert, gratuit et largement utilisé. Si les données sont enregistrées dans une ressource qui est accessible via un site internet, ce critère est automatiquement rempli. 
<span class="left-indent-bold">Le jeu de données est accessible via le dépôt Zenodo (voir Zenodo-FAIR Principles).</span>
<span class="left-indent-bold">FAIR: A1.1 - rempli.</span>
{: .ml-6 }

3.2.4. Vérifier que les données sont accessibles via un protocole de communication qui permet, si nécessaire, de mettre en place une procédure d'authentification et d’autorisation. 
<span class="left-indent-bold">Si nécessaire, il est possible de restreindre l’accès aux données mises en ligne dans le dépôt Zenodo (voir Zenodo-FAIR Principles).</span>
<span class="left-indent-bold">FAIR: A1.2 - rempli.</span>
{: .ml-6 }

3.2.5. Vérifier que les métadonnées seront accessibles même lorsque les données elles-mêmes ne seront plus disponibles. (De façon ordinaire ce critère est considéré comme rempli, si la condition F4 est satisfaite).
<span class="left-indent-bold">Le dépôt Zenodo garantit l’accessibilité des métadonnées durant toute l’existence du dépôt (voir Zenodo-FAIR Principles).</span>
<span class="left-indent-bold">FAIR: A2 - rempli.</span>
{: .ml-6 }






**************






![](/assets/images/figure1.jpg){:width="70%" .d-block .mx-auto}

##### Figure 1. Principes FAIR et écosystème basé sur un dépôt institutionnel dans le contexte du cycle de vie des données.
{: .no_toc .text-center .mb-5 }











