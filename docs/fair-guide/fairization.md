---
layout: default
title: Étapes de la FAIRisation
parent: Guide FAIR
nav_order: 2
---

# Étapes de la FAIRisation
{: .no_toc }

Les étapes suivantes décrivent le processus complet de la FAIRisation qui peut être appliqué à un jeu de données d’un corpus afin que ce dernier réponde à tous les critères FAIR. Ce programme de la FAIRisation fait appel à un écosystème FAIR basé sur un dépôt des données institutionnel (sur les différents écosystèmes FAIR, voir _supra_ [“Écosystème FAIR”](/docs/fair-guide/presentation.html#écosystème-fair){:target="_blank"}).
{: .fs-6 .fw-300 }

<details open markdown="block">
  <summary>
    Table des matières
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## 1. Vérification des données

1.1. S’assurer que les langages et les formats/extensions utilisés pour l’encodage des données sont connus, largement utilisés et, de préférence, libres. (_Il est impossible de définir in fine ce qui est un format/langage “connu” ou “largement utilisé”. On s’appuyer donc sur le bon sens… Privilégiez toujours les formats libres, par exemple csv (format libre) au lieu de xls (format propriétaire de Microsoft), txt (format libre) au lieu de doc (format propriétaire de Microsoft), etc. Pour plus d’informations sur le choix des formats à privilégier pour la pérennité des données de la recherche voir [ce recensement](https://dans.knaw.nl/en/about/services/easy/information-about-depositing-data/before-depositing/file-formats)_). Si cela n’est pas le cas, expliquer clairement ce qui a dicté le choix d’un langage ou d’un format particulier et indiquer tous les logiciels (nom, version, système d’exploitation) et outils nécessaires pour la lecture des données. (_Ces informations seront par la suite utilisées dans les métadonnées_). **FAIR: I1**

1.2. S’assurer que les données sont explicites et compréhensibles en l’état. Cela signifie que toutes les abréviations, tous les termes ambigus ou toutes les balises utilisées dans la description des données doivent être clairement expliqués ou avoir déjà une documentation existante. (_Pour plus d’informations sur les différents standards voir [ce recensement](http://rd-alliance.github.io/metadata-directory/standards/)_).

<span class="margin-top-reduction">Trois options sont possibles: i) les données sont explicites en l’état; ii) les données ne sont pas explicites et sont accompagnées d’une documentation détaillée personnelle; iii) les données ne sont pas explicites et sont accompagnées d’un renvoi vers une documentation détaillée déjà existante (par exemple TEI P5 TEI Guidelines). (_Ces informations seront par la suite utilisées dans les métadonnées_). **FAIR I2**</span>


## 2. Préparation des métadonnées

### 2.1. Préparation des métadonnées complètes.

2.1.1. S’assurer que les métadonnées contiennent le plus de détails possible. (_Se référer au modèle des métadonnées détaillées, voir [Annexe 4](/docs/fair-guide/annexe-4){:target="_blank"}_) **FAIR: F2**

2.1.2. S’assurer que les données disposent une licence et qu’elle est clairement mentionnée dans les métadonnées. (_Les données peuvent avoir tous types de licence, y compris les licences “non libres de droits”_). **FAIR: R1.1**

2.1.3. S’assurer que les métadonnées contiennent un historique détaillé de la provenance des données. (_Par exemple, les données peuvent être produites durant un autre projet et ensuite réutilisées, corrigées et modifiées par le présent projet_). **FAIR: R1.2**

2.1.4. S’assurer que les données utilisent des standards (s’il en existe) de présentation, d’organisation ou d’archivage communément utilisés dans le domaine scientifique auquel ces données appartiennent. (_Ces informations seront par la suite utilisées dans les métadonnées_).

<span class="margin-top-reduction">(_Bien qu’un “standard” commun ne semble pas exister en sciences humaines et sociales, certains projets ou programmes de recherche peuvent s’appuyer sur des conventions similaires. Par exemple, l’organisation des données dans le même type de tableau, l’utilisation des mêmes principes de balisage, etc. Si c’est le cas, ces conventions doivent être mentionnées, par exemple dans les métadonnées. Ne pas confondre avec I2. Le I2 vise à rendre les données compréhensibles / interopérables grâce à la documentation associée à ces données. Le R1.3 vise à faciliter la réutilisation des données grâce aux indications générales sur les standards et les conventions sur lesquels les données s’appuient. Pour plus d’informations sur les différents standards voir [ce recensement](http://rd-alliance.github.io/metadata-directory/standards/)_) **FAIR: R1.3**</span>

### 2.2. Relier les données.

S’assurer que dans les cas où les présentes données peuvent être reliées à d’autres données (par exemple, les données textuelles peuvent être reliées aux images des manuscrits), les métadonnées contiennent des références à ces données reliées (par exemple le PID des données reliées, voir F1). Le type de lien entre les données doit être explicitement mentionné. (Par exemple, “ce texte <u>est la transcription</u> de ce manuscrit” ou “ce texte <u>a été écrit</u> par cette personne”). **FAIR: I3**

## 3. Mise des données dans un dépôt

### 3.1. Enregistrement des données et des métadonnées.

3.1.1. Choisir une ressource consultable (par exemple, un dépôt de données) qui répond à tous les critères FAIR applicables aux métadonnées (F1, F3, F4, A1.1, A1.2, A2, I1, I2, I3, R1.1, R1.2, R1.3). La plupart des grands dépôts de données affichent de façon claire leur conformité aux critères FAIR. (_Pour plus de détails sur le choix de dépôt et sur les critères FAIR auxquels il doit répondre voir infra [Annexe 3](/docs/fair-guide/annexe-3){:target="_blank"}_)

3.1.2. Enregistrer les données et les métadonnées y associées dans une ressource consultable choisie précédemment. **FAIR: F4**

### 3.2. Vérification de l’accessibilité et de l’exactitude des (méta)données.

3.2.1. Vérifier que les données possèdent un identifiant persistant et unique (PID) (fourni par la ressource où les données sont enregistrées). **FAIR: F1**

3.2.2. Vérifier que le PID des données est mentionné dans les métadonnées. **FAIR: F3**

3.2.3. Vérifier que les données sont accessibles via un protocole de communication ouvert, gratuit et largement utilisé. Si les données sont enregistrées dans une ressource qui est accessible via un site internet, ce critère est automatiquement rempli. (_Par un protocole de communication “ouvert, gratuit et largement utilisé”, on entend avant tout un protocole informatique libre et connu comme HTTP/HTTPS (=site web), FTP etc. Les autres “protocoles de communications” qui s’appuient sur des logiciels propriétaires et non universellement implantés (par exemple Skype, Microsoft Exchange Server, etc.) ne répondent pas à ce critère_). **FAIR: A1.1**

3.2.4. Vérifier que les données sont accessibles via un protocole de communication qui permet, si nécessaire, de mettre en place une procédure d'authentification et d’autorisation. (_FAIR data ne signifie pas OpenData. Le protocole via lequel les données et les métadonnées sont accessibles, doit avoir la possibilité, en cas de besoin, de restreindre l’accès aux données , par exemple uniquement aux utilisateurs possédant un login et un mot de passe_). **FAIR: A1.2**

3.2.5. Vérifier que les métadonnées seront accessibles même lorsque les données elles-mêmes ne seront plus disponibles. (_De façon ordinaire ce critère est considéré comme rempli, si la condition F4 est satisfaite_). **FAIR: A2**
 
---

#### À suivre: [Bibliographie](/docs/fair-guide/bibliography)
{: .no_toc .text-right .fs-3 .fw-400 .text-grey-dk-100 }
