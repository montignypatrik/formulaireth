# Formulaire TH imprimable

Page HTML statique qui transforme une **demande de tarif horaire** FACNET (facturation.net)
en formulaire papier « Demande de paiement — Tarif horaire » prêt à signer.

## Utilisation

1. Ouvrez `index.html` dans Chrome, Edge ou Firefox (double-clic, aucun serveur requis).
2. Dans FACNET, ouvrez la demande puis *Fichier › Enregistrer sous… › Page Web* (fichier `.html`),
   ou copiez le code source de la page.
3. Déposez le ou les fichiers `.html` dans la zone prévue (ou collez le code source).
4. Cliquez **Imprimer / Enregistrer en PDF** et choisissez « Enregistrer au format PDF »
   ou votre imprimante.

Plusieurs demandes peuvent être chargées en même temps : chacune est imprimée sur sa propre page.
Tout est traité localement dans le navigateur ; aucune donnée n'est envoyée.

## Données reprises

- Numéro de la demande (Nce), professionnel (prénom, nom, numéro, compte administratif, spécialité)
- Établissement (nom, numéro, secteur d'activité) et période
- Lignes d'activité : date, mode, plage horaire (NU/AM/PM/SO), réf., code d'activité, secteur (SD), heures
- Total des heures
- Renseignements complémentaires et frais de déplacement (si la section était ouverte au moment
  de l'enregistrement de la page)
- Noms et dates des signataires (professionnel/mandataire et établissement), avec des zones de signature

L'option « Pré-remplir les dates de signature vides » inscrit la date du jour dans les champs Date vides.
