CLEConfig — Configurateur pour CLE.html
========================================

CONTEXTE
--------
CLEConfig s'inscrit dans la chaîne de gestion financière des clochers :

  CLEConfig  →  CLE  →  Impression  →  Secrétariat / Trésorière  →  CLUP

1. CLEConfig configure CLE pour un clocher donné (nom, périodicité, catégories)
2. La trésorière remet au responsable local les différents fichiers CLE générés
3. Le responsable local utilise CLE pour encoder les recettes et dépenses
4. Il imprime le tableau et le transmet au secrétariat inter-paroissial
   et à la trésorière
5. Le responsable local verse le montant indiqué sur le compte bancaire inter-paroissial
6. La trésorière encode dans CLUP le total des recettes, le total des
   dépenses et le fonds de caisse éventuel


DESCRIPTION
-----------
CLEConfig est une application web autonome (fichier HTML unique) permettant
de configurer CLE.html sans éditer le code source.
Elle fonctionne directement dans le navigateur, sans installation,
sans serveur, sans connexion internet.


UTILISATION
-----------
Ouvrir CLEConfig.html dans un navigateur web (Chrome recommandé).

Étape 1 : Charger CLE.html
  Cliquer "Choisir CLE.html" et sélectionner le fichier CLE.html à configurer.

Étape 2 : Modifier les paramètres
  - Nom du clocher : sélectionner dans le déroulant des 17 clochers
  - Périodicité : Mois / Trimestre / Semestre / Année

Étape 3 : Générer
  Cliquer "Générer CLE.html" — le fichier configuré est téléchargé
  dans le dossier Téléchargements.
  Remplacer l'ancien CLE.html par le nouveau fichier généré.

Note : les catégories (onglets de CLE) sont fixes et ne peuvent pas
être modifiées via CLEConfig.


COMPATIBILITÉ
-------------
Testé sous : Chrome, Edge
Fonctionne également sous : Firefox, Safari (fonctions de base)
