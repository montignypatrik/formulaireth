# Formulaire TH imprimable

Page HTML statique qui transforme une **demande de tarif horaire** FACNET (facturation.net)
en formulaire papier prêt à signer, reproduisant la mise en page du formulaire RAMQ **1215**
« Demande de paiement — Tarif horaire, honoraires forfaitaires et vacation » (voir `1215.pdf`).

## Utilisation

1. Ouvrez `index.html` dans Chrome, Edge ou Firefox (double-clic, aucun serveur requis).
2. Dans FACNET, ouvrez la demande puis *Fichier › Enregistrer sous… › Page Web* (fichier `.html`),
   ou copiez le code source de la page.
3. Déposez le ou les fichiers `.html` dans la zone prévue (ou collez le code source).
4. Cliquez **Imprimer / Enregistrer en PDF** et choisissez « Enregistrer au format PDF »
   ou votre imprimante.

Plusieurs demandes peuvent être chargées en même temps : chacune est imprimée sur sa propre page.
Comme sur le 1215, une feuille contient 15 lignes (réf. 1 à 45) ; au-delà, la demande continue sur
une feuille supplémentaire et le total, les frais et les signatures figurent sur la dernière.
Tout est traité localement dans le navigateur ; aucune donnée n'est envoyée.

## Données reprises

- Numéro de la demande (Nce) → *Numéro de contrôle externe*
- Professionnel : prénom, nom, numéro, compte administratif (→ *Nº du groupe*)
- Établissement (nom, numéro) et période (dimanche–samedi, en année / mois / jour)
- Lignes d'activité : quantième (jour du mois), mode, plage horaire (nuit/AM/PM/soir), code d'activité,
  secteur de dispensation, heures
- Total des heures
- Renseignements complémentaires et frais de déplacement (si la section était ouverte au moment
  de l'enregistrement de la page)
- Noms et dates des signataires (professionnel/mandataire et établissement), avec des zones de signature

L'option « Pré-remplir les dates de signature vides » inscrit la date du jour dans les champs Date vides.
