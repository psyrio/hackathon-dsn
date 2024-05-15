# Hackathon DSN

Dépôt pour le Hackathon DSN organisé par la Direction interministérielle du numérique.

**📙 Retrouvez le Guide du participant sur Outline en cliquant [ici](https://documentation.beta.numerique.gouv.fr/doc/guide-hackathon-dsn-Vvxa7bq3O0)**

## 👩‍💻 Comment participer ? 

Pour participer au Hackathon vous devez créer un dépôt public (vous pouvez par exemple partir d'un fork de ce dépôt en cliquant [ici](https://github.com/etalab-ia/Hackathon-DSN/fork) puis sur *"Create fork"*).

Votre dépôt servira pour l'évaluation de votre projet à l'issu du Hackathon ! 

Bon courage 🔥!

## 🌸 Rendu

Pour évaluer votre projet merci de compléter ce README avec les informations suivantes : 

### Description

Problème de traitement des données concernant les indémnités journalières (IJSS) des arrêts de travail pour l'ensemble des acteurs.
Les entreprises et les tiers déclarants doivent télécharger manuellement les retours de la CPAM (Fichiers BPIJ et les comptes rendus) pour ensuite comparer avec ce qu'il existe en paie pour comprendre les anomalies et les correctifs à apporter pour le bon traitement des arrêts et le paiement des IJSS.  
Les entreprises appelent souvent la CPAM (environ 1h30 en moyenne par arrêt) par téléphone pour analyser avec eux, comprendre les problèmes et voir comment les résoudre.

Côté citoyen, lorsqu'il n'a pas encore touché ces indémnités, il appelle son entreprise, mais en fonction, l'entreprise peut le renvoyer aussi vers la CPAM.

Côté CPAM, le fait d'avoir autant d'appels, cela overbook sont standard et entraine des délais de traitement de plus en plus en plus long.
Cela peut engendrer également des mauvaises indémnisations.

Côté entreprise, le temps perdu avec la CPAM, la difficulté d'avance d'IJSS sur des salariés qui sont sur le départ sans avoir la certitude que l'arrêt est bien arrivé à la CPAM, ou pour les nouveaux arrivant pour qui l'entreprise n'a pas les éléments nécessaires au calcul précis de l'IJSS fait peser un risque sur sa trésorerie.

### Solution


Ajout de données dans la DSN (soit via l'ajout de rubriques dans le bloc G00.66 soit en créant un nouveau bloc) et dans le BPJI afin de permettre un croisement optimal automatisé permettant rapidement de remonter les problèmes rencontrés et les informations nécessaires à la prise en charge des IJSS par l'entreprise et la CPAM.

### Impact envisagé

Utilisation de la DSN et du BPIJ en automatisant les contrôles et les remontées à travers un portail unifié pour tous les acteurs sur NET ENTREPRISE.

Création d'une nouvelle interface dans Mon Espace Santé afin que les citoyens puissent accéder à un suivi des traitements de leurs arrêts de travail et du versement des indémninités en fonction du payeur (Entreprise ou CPAM).

Mise en place de contrôles précis sur les montants des IJSS, les périodes d'indémnisations et des dépôts des élémnents nécessaires au traitement (Certificat reçu par la CPAM,...).

### Ressources

* Présentation en powerpoint du projet, des règles de gestion et contrôles.
* Modèle de données DSN et BPIJ 

