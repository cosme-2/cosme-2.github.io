---
layout: default
title: Questions fréquentes
nav_order: 5
---

# Questions fréquentes
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

## Questions générales

### Qu’est-ce que FAIR?

FAIR est une abréviation de _Findable (= Facile à trouver)_, _Accessible_, _Interoperable (= Interopérable)_, _Reusable (= Réutilisable)_. Il s’agit de principes directeurs ou de recommandations (et non pas d’un standard) qui doivent être appliqués aux données de la recherche. Le but de la mise en place des principes FAIR est de rendre les données scientifiques plus accessibles et plus compréhensibles et leurs sauvegarde et réutilisation plus pérennes.

<span class="margin-top-and-italic">Pour plus de détails, voir ["Qu’est-ce que FAIR?"](/docs/fair-guide/presentation.html#quest-ce-que-fair)</span>
{: .fs-4 .fw-300 }

### Pourquoi FAIRiser les données?

Suivre les recommandations FAIR vise à permettre de garder les données propres, compréhensibles, pérennes et faciles à partager et, si nécessaire, à protéger légalement. En outre, le respect de ces recommandations et de plus en plus requis par de différents organismes de financement et leur application peut être un atout majeur lors des appels à projets.

<span class="margin-top-and-italic">Pour plus de détails, voir ["Pourquoi FAIRiser les données?"](/docs/fair-guide/presentation.html#pourquoi-fairiser-les-données)</span>
{: .fs-4 .fw-300 }

### Comment FAIRiser les données?

Bien qu’il revienne à chaque projet de choisir les moyens par lesquels il souhaite atteindre les différents principes FAIR, il est possible d’envisager deux approches: la mise des données dans un dépôt de données institutionnel ou l’élaboration d’une infrastructure personnelle de gestion des données. Si, pour une raison ou une autre, vous voulez garder la main sur la totalité du processus et si vous avez la possibilité de faire accomplir les tâches techniques lourdes par du personnel compétent vous pouvez opter pour l’infrastructure personnelle, dans tous les autres cas, il vaut mieux se tourner vers un dépôt des données.

<span class="margin-top-and-italic">Pour plus de détails, voir ["Écosystème FAIR"](/docs/fair-guide/presentation.html#écosystème-fair)</span>
{: .fs-4 .fw-300 }

### Quelles données faut-il FAIRiser?
Une “_unité des données_” à laquelle les principes FAIR sont appliqués est communément désignée comme un “_Objet Digital FAIR_” (_FAIR Digital Object_, FDO). C’est à ce FDO que les identifiants pérennes et les métadonnées sont associés. Cependant, les principes FAIR indiquent seulement que le FDO doit être “_une entité significative_” pour la FAIRisation. Il appartient donc à chaque projet de faire le choix de “_l’unité_” de la FAIRisation. En pratique, il est possible de FAIRiser soit un jeu de données qui regroupe alors toutes les données d’un corpus, soit une unité “atomique” d’un corpus (par exemple, une notice, un document, une image…). Il faut garder à l’esprit toutefois que la FAIRisation des unités atomiques, une par une, signifiera de déposer dans un dépôt des données (si cette approche est choisie) des centaines/milliers de fichiers, un par un. Et cela ne semble pas être raisonnable à l’échelle d’un corpus.

<span class="margin-top-reduction">À noter également que des corpus constitués des données d’une nature différente (par exemples, données textuelles, visuelles, chiffrées, etc.) peuvent regrouper chaque type de données dans un jeu de données séparé. Autrement dit, au sein d’un même corpus il peut exister plusieurs jeux de données où chaque “_jeu_” réunit des données analogues, par exemple les images, les textes, les notes, etc.</span>

<span class="margin-top-and-italic">Pour plus de détails, voir ["Jeu de données"](/docs/fair-guide/presentation.html#jeu-de-données)</span>
{: .fs-4 .fw-300 }

### Comment choisir la licence pour les données?

Il existe plusieurs outils qui aident à choisir la licence la plus adaptée à vos données. On signalera avant tout [l’outil de choix des licences](https://chooser-beta.creativecommons.org){:target="_blank"} de Creative Commons et [l’outil de choix des licences open sources](https://choosealicense.com){:target="_blank"} de GitHub.

<span class="margin-top-and-italic">Pour plus de détails, voir par exemple [“À propos des licences”](https://creativecommons.org/licenses/?lang=fr){:target="_blank"} de Creative Commons.</span>
{: .fs-4 .fw-300 }

---

## Dépôt de données

### Comment choisir un dépôt de données institutionnel?

Voir [Annexe 3. Choix d’un dépôt de données](/docs/fair-guide/annexe-3).


### Comment constituer un dossier de dépôt pour les données?

De préférence, un dossier de dépôt doit contenir, mis à part les données elles-mêmes, un document “_README_” avec toutes les informations qui décrivent les données déposées aussi que toute la documentation nécessaire pour la meilleure compréhension des données.

<span class="margin-top-and-italic">Pour l’exemple du document “_README_” et de la structure du dossier de dépôt, voir le dossier ["Dataset-upload-example"](https://github.com/cosme-2/FAIR-examples/tree/main/dataset-upload-example){:target="_blank"}</span>
{: .fs-4 .fw-300 }

---

## Infrastructure personnelle

### Est-ce que les données hébergées sur un site type Drupal/WordPress sont FAIR?

Non. D’ordinaire, les sites web développés sur la base d’un [CMS](https://fr.wikipedia.org/wiki/Syst%C3%A8me_de_gestion_de_contenu){:target="_blank"} (un système de gestion de contenu de type WordPress, Joomla, Drupal, etc.) stockent leurs données en tant que base des données relationnelles sous le format SQL. Les corpus qui s’appuient sur ces sites auront ainsi leurs données stockées en SQL. Bien que du point de vue technique le SQL soit un langage connu et largement utilisé (donc conforme au critère _FAIR: I1_), les bases des données relationnelles de ces plateformes ne sont pas conçues ab initio pour sauvegarder les données de la recherche, mais pour faire fonctionner un site web. De fait, il peut être délicat d’extraire, à partir de ces sites, le fichier SQL qui contient uniquement les données d’un corpus particulier. En outre, un site web bâti avec un CMS ne procure pas, de façon automatique, ni les identifiants pérennes ni le système approprié de gestion des métadonnées (champs spécifiques, langage, vocabulaire, ontologie des métadonnées…). 

<span class="margin-top-reduction">En conclusion, les données hébergées sur ce type de site sont, de point de vue théorique, “interopérables” (car stocké en SQL), mais, en pratique, difficile à manipuler (extraction, partage, gestion des métadonnées…). Donc non, l’utilisation d’un site construit sur un CMS ne rend pas automatiquement les données conformes aux principes FAIR.</span>

### Est-ce qu’une “_adresse web_” peut être un identifiant unique?

Pour que le critère _FAIR: F1_ soit rempli, l’identifiant des données (_PID_) doit, de préférence, être délivré par une autorité qui peut garantir sa pérennité. Une URL (_Uniform Resource Locator_, communément appelée “_adresse web_”) peut, à certains égards, répondre à ce critère, mais son utilisation doit être déconseillée à cause de son caractère instable.

<span class="margin-top-and-italic">Pour plus de détails, voir [[7](/docs/fair-guide/bibliography#7){:target="_blank"}], [[15](/docs/fair-guide/bibliography#15){:target="_blank"}].</span>
{: .fs-4 .fw-300 }

