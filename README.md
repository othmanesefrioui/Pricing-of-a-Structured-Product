## French Version

# Pricing-of-a-Structured-Product

## Description du Projet

Ce projet vise à modéliser et évaluer le prix d'un produit structuré de type Athena, émis par la Société Générale. Un produit structuré est un instrument financier dérivé combinant plusieurs actifs pour répondre à des objectifs de risque et de rendement spécifiques.

Le produit structuré étudié ici est lié à l'indice EURO STOXX 50®.

## Contenu du Projet

1. **Athena.ipynb**:
   - Ce notebook Jupyter contient le code et les calculs nécessaires pour modéliser le produit structuré Athena.
   - Les principales étapes incluent l'importation des données, la définition des paramètres du produit, la simulation des scénarios de marché et le calcul des remboursements possibles.
   - Les simulations sont basées sur les conditions du marché et les formules de remboursement définies dans les termes et conditions du produit.

2. **Termsheet Athena SocieteGenerale.pdf**:
   - Ce document PDF fournit les détails spécifiques du produit structuré Athena émis par la Société Générale.
   - Il inclut des informations telles que la date de transaction, la date d'évaluation, la valeur nominale, les conditions de remboursement et les risques associés.
   - Les principaux points à noter sont :
     - **Durée**: 3 ans
     - **Montant Nominal Total**: EUR 2 000 000
     - **Capital Garanti**: Non
     - **Sous-jacent**: EURO STOXX 50®
     - **Remboursement Final**: Basé sur la performance de l'indice sous-jacent et des conditions de barrière activante.
     - **Remboursement Anticipé**: Possible si certaines conditions de performance sont remplies lors des dates d'évaluation.
