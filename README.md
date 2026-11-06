# STARK — Devis & Factures

Application web statique en français, conçue pour être publiée sur GitHub Pages.

## Fonctionnalités
- Catalogue de prestations réutilisables (nom, description, activité, unité, prix).
- Carnet clients.
- Création de devis et factures avec lignes, quantités et calculs automatiques.
- Conversion d'un devis en facture.
- Statut de paiement, impression / export PDF via la fonction Imprimer du navigateur.
- Tableau de bord et sauvegarde / restauration JSON.
- Interface responsive téléphone et ordinateur.
- TVA à 0 % selon le choix « sans TVA » ; la mention de franchise en base est affichée à titre indicatif et doit être vérifiée selon votre situation.

## Mise en route
1. Décompresser l'archive.
2. Créer un dépôt GitHub et téléverser `index.html` et `README.md`.
3. Dans GitHub : **Settings → Pages → Deploy from a branch → main → /(root) → Save**.
4. Ouvrir l'adresse GitHub Pages fournie.

## Données
Les données sont stockées dans le `localStorage` du navigateur et sur l'appareil utilisé. Elles ne sont pas synchronisées automatiquement entre téléphone et ordinateur. Utilisez régulièrement **Exporter mes données** et importez la sauvegarde sur l'autre appareil.

## À compléter avant usage professionnel
Renseigner les coordonnées et le SIRET. Vérifier les mentions obligatoires, les règles de numérotation, les conditions de paiement et la mention TVA applicables à votre situation. Cette première version est un outil de gestion et ne remplace pas une validation comptable ou juridique.
