# scriptInvestmentReitDemo

## Description
Ce script automatise l'investissement dans des tokens REIT en fonction d'un rendement attendu. Il surveille une plateforme REIT pour détecter les nouvelles ventes et effectue des actions automatisées pour acheter les produits répondant aux critères de rendement.

## Fonctionnalités
- Vérification du rendement attendu sur une plateforme REIT.
- Déclenchement d'un minuteur lorsque de nouveaux produits sont disponibles.
- Vérification du rendement attendu à la fin du minuteur.
- Définition de la quantité de produit à acheter.
- Ajout automatique du produit au panier.
- Passage automatique à la caisse avec sélection du mode de paiement et de la devise.
- Acceptation des conditions générales et finalisation de l'achat.
- Verrouillage du produit pour un examen minutieux avant le paiement final.

## Utilisation
1. Ouvrez le fichier `addProfitableInvestment.js` et modifiez les paramètres selon vos besoins.
2. Exécutez le script sur la plateforme REIT cible.

## Configuration
- `productId`: Identifiant du produit à surveiller.
- `checkExpectedIncome()`: Fonction pour vérifier le rendement attendu.
