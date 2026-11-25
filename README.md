# Cotation

**La bonne cotation NGAP, en quelques secondes.** Pour tous les médecins, généralistes, pédiatres et spécialistes, en ville comme à l’hôpital, selon votre spécialité et votre secteur.

👉 **https://baptistemazas-nutrition.github.io/cotation/**

![Aperçu](og-image.png)

## Ce que fait l’outil

- Vous collez la fiche du patient (Doctolib, ORBIS, courrier d’adressage) ou vous répondez à quelques questions : motif, adressage, âge, couverture, lieu, acte associé, urgence ou régulation, horaire.
- Il donne les codes à saisir (par exemple `CS + MCS + MCE`, `G + MEG`, `VG + MDN`), le montant de base, le mode de facturation (tarif opposable ou dépassement), ce qu’il faut faire pour être en règle (courrier au médecin traitant, devis…) et les pièges à éviter.
- Il explique chaque cotation : avis ponctuel (`APC`, `APY`, `APU`), majorations de coordination (`MCS`, `MCG`, `MCC`), d’âge (`MEG`, `MOP`, `MP`), de spécialité (`MCE`, `MCY`…), consultations complexes et très complexes, cumul avec un acte technique.

## Couverture

- **Médecine générale** : `G`, `VG`, `MEG`, `MCG`, `MOP`, consultations longues du médecin traitant (`GL1` à `GL3`), examens obligatoires de l’enfant (`COE`, `COB`, `COD`), visites (`MD`, `MDN`, `MDI`, `MDD`, `MU`), consultations complexes.
- **Pédiatrie** : `CEH`, `CEK`, `CEG`, `NFP`, examens obligatoires (`COH`, `COK`, `COG`), consultation de recours `CEP`, consultations complexes et très complexes.
- **Spécialités** : cardiologie, chirurgie (toutes spécialités), dermatologie, endocrinologie-diabétologie-nutrition, gastro-entérologie, gériatrie, gynécologie médicale et obstétrique, hématologie-oncologie, maladies infectieuses, médecine interne, MPR, médecine vasculaire, néphrologie, neurologie, ophtalmologie, ORL, pneumologie, psychiatrie et pédopsychiatrie, rhumatologie, stomatologie, et autres spécialités.
- **Situations** : avis ponctuel, accès direct, téléconsultation et téléexpertise (`TE2`, `RQD`), urgences de nuit, du dimanche et des jours fériés, garde régulée (`CRN`, `CRM`, `CRD`, `VRN`…), patients adressés par le SAS (`SNP`, `SHE`, `MRT`, `MVR`), `MCU`, `MUT`.
- **Secteurs** : secteur 1 et hôpital (tarif opposable, `APU` pour les PU-PH), secteur 2 OPTAM (dépassement maîtrisé), secteur 2 non OPTAM.
- **Non couverts** : professions de santé non médicales (infirmiers, kinésithérapeutes, sages-femmes…), forfaits (forfait médecin traitant, rémunérations sur objectifs). Les 8 000 actes techniques CCAM ne sont pas listés : l’outil applique leurs règles de cumul avec la consultation.

## Utilisation

1. Choisissez votre spécialité et votre secteur dans « Mon exercice » (mémorisé sur votre appareil).
2. Collez la fiche du patient avec Ctrl+V n’importe où dans la page, ou répondez aux questions.
3. Copiez les codes.

**Sur Doctolib**, un favori à glisser dans la barre du navigateur ouvre l’outil par-dessus la fiche du rendez-vous et le pré-remplit (onglet « Doctolib et partage »). **Depuis ORBIS** ou un autre logiciel, utilisez le copier-coller.

**Hors ligne** : le fichier `index.html` fonctionne seul, d’un double-clic, sans connexion.

## Confidentialité

Tout se passe dans votre navigateur : aucune donnée saisie n’est envoyée, aucun compte, aucun cookie, aucune mesure d’audience. Seules les polices de caractères sont chargées depuis Google Fonts.

## Sources

- [Tarifs conventionnels des médecins, ameli.fr](https://www.ameli.fr/medecin/exercice-liberal/facturation-remuneration/consultations-actes/tarifs/tarifs-conventionnels-medecins-generalistes-specialistes)
- [NGAP au 1er janvier 2026](https://www.syngof.fr/wp-content/uploads/2026/01/NGAP-01012026.pdf)
- [Convention 2024, annexe 1 : tarifs de tous les codes NGAP](https://www.fmfpro.org/wp-content/uploads/2024/06/Convention2024_ANNEXE_1-NGAP_VDF.pdf)
- [Annexe 1 : cotations par spécialité au 1er janvier 2026](https://circulaires.ameli.fr/sites/default/files/directives/CIR-DDGOS-Convention%20M%C3%A9dicale%20Annexe-1.pdf)
- [Annexe 2 : calendrier des revalorisations](https://circulaires.ameli.fr/sites/default/files/directives/CIR-DDGOS-Conv.%20M%C3%A9d.%202024_Calendrier%20nomenclature-annexe%202.pdf)
- [Annexe 3 : actes CCAM cumulables avec la consultation](https://circulaires.ameli.fr/sites/default/files/directives/CIR-DDGOS-Convention%20M%C3%A9dicale%20Annexe-3.pdf)
- [Circulaire CIR-32/2024 : généralistes, pédiatres, psychiatres, cumuls](https://circulaires.ameli.fr/sites/default/files/directives/cir/2024/CIR-32-2024.pdf)
- [Circulaire CIR-14/2025](https://circulaires.ameli.fr/sites/default/files/directives/cir/2025/CIR-14-2025.pdf)

## Avertissement

Aide à la décision, pas un avis juridique : la NGAP en vigueur sur ameli.fr et la CPAM font foi. Règles vérifiées en novembre 2026.

Une erreur, une situation à ajouter ? [Ouvrez un ticket](https://github.com/baptistemazas-nutrition/cotation/issues).

Conçu par le Dr Baptiste Mazas, endocrinologie, diabétologie et nutrition.

## Propriété intellectuelle

© 2026 Baptiste Mazas, tous droits réservés. L'outil en ligne est libre d'utilisation pour coter vos consultations. Le code, les textes et le design ne peuvent être ni copiés, ni modifiés, ni redistribués, ni exploités commercialement sans mon accord écrit : voir la [licence](LICENSE).

Vous souhaitez développer ce projet avec moi, l'intégrer à votre offre ou obtenir une licence ? Écrivez-moi sur [LinkedIn](https://www.linkedin.com/in/baptiste-mazas-577219182/).
