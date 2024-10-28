#### Projet effectué dans le cadre de ma formation chez OpenClassrooms

# Analyse des Ventes d'une Librairie avec Python

<p align="center">
  <img src="https://github.com/MurielleGK/Analyse_ventes/blob/main/data/logo.jpg?raw=true" alt="La poule qui chante" width="300"/>
</p>

## Contexte du Projet

Dans le rôle d'une **data analyste** chez Lapage, j'ai été chargé de réaliser une analyse approfondie de la performance de leur site de vente en ligne, lancé il y a deux ans suite à un engouement croissant de la part des clients et au succès de certains produits. Mon rôle était d’exploiter ces deux années d’activité en ligne pour évaluer les points forts et faibles de l’entreprise, de fournir des insights clés concernant les ventes et les comportements des clients de la librairie en ligne pour répondre aux besoins en stratégie commerciale et en marketing.

## Objectifs du Projet

1. **Profiler et comprendre le comportement des clients** :
   - Analyser la corrélation entre le genre des clients et les catégories de livres achetés.
   - Examiner la relation entre l'âge des clients et différents indicateurs (montant total des achats, fréquence d'achat, panier moyen, catégories de livres).

2. **Analyser le chiffre d'affaires** :
   - Décomposer l'évolution du chiffre d'affaires dans le temps en utilisant des moyennes mobiles pour évaluer les tendances générales.
   - Analyser les tendances du chiffre d’affaires et identifier les produits les plus et les moins performants.
   - Utiliser la **courbe de Lorenz et le coefficient de Gini** pour évaluer la répartition du chiffre d'affaires entre les clients.

3. **Recommandations** :
   - Faire des recommandations stratégiques basées sur l'analyse des données.

## Outils

- **Python** pour l'analyse des données
- **Pandas** pour la manipulation des DataFrames
- **Matplotlib et seaborn** pour la visualisation des tendances et des corrélations
- **Scipy** pour la réalisation des tests statistiques (chi-carré, corrélation de Pearson,Test de Kolmogorov-Smirnov,Test de Shapiro-Wilk,Test d’Anderson-Darling, Test K-S)
- **scikit-learn** pour la modélisation prédictive (LinearRegression et PolynomialFeatures) 
- **Jupyter Notebook** pour le développement de l'analyse
- Les fichiers sources incluent les données clients, les produits, et les transactions disponibles sous format CSV.

## Démarches

### 1. Préparation des données
J'ai commencé par le nettoyage, la fusion des datasets (`customers.csv`, `products.csv`, `transactions.csv`) et la standardisation des formats pour assurer la cohérence des analyses. Ensuite j'ai fusionné les fichieres et traité les valeurs manquantes.

### 2. Analyse des ventes
- J'ai réalisé une analyse temporelle du chiffre d’affaires et appliqué une moyenne mobile pour lisser les tendances.
- J'ai identifié les produits les plus et les moins performants et visualisé les catégories les plus rentables.

### 3. Évaluation des inégalités
- J'ai utilisé la **courbe de Lorenz** et calculé le **coefficient de Gini** pour comprendre la répartition des revenus entre les clients.

### 4. Profilage et corrélations clients
- J'ai étudié les corrélations entre l’âge des clients et leurs comportements d’achat (montant total, fréquence, taille du panier, catégories de livres).
- J'ai analysé les préférences de genres pour identifier d’éventuelles tendances par groupe démographique.


## Résultats Clés

- **Tendances de Vente** : J’ai pu identifier des pics et creux dans les ventes, avec une tendance globale croissante observée après application de la moyenne mobile.
- **Corrélations Client** : J’ai constaté une corrélation significative entre l'âge des clients et la taille de leur panier moyen, indiquant que les clients plus jeunes ont tendance à avoir des paniers plus importants.
- **Répartition des Revenus** : La courbe de Lorenz met en évidence une concentration marquée du chiffre d'affaires auprès d'un segment restreint de clients (coefficient de Gini élevé), justifiant une segmentation plus fine pour augmenter la rentabilité et l'engagement de ce groupe clé.

## Recommandations

1. **Optimisation des offres par tranche d'âge ( [18-30[, [30- 50[, +50) et catégorie de produits**
2. **Segmentation des clients professionnelles et particuliers , sous segmentation des clients farticulier en fonction des tranches d'âge et stratégies ciblées**
3. **Réduction de l’inégalité du chiffre d'affaires entre les clients**
4. **Renforcement de l’engagement client, de sa fidélisation et augmentation de la taille moyenne du panier**
5. **Analyse temporelle et préparation des saisons de vente**
6. **Automatisation des processus et utilisation de l’analyse prédictive**

## Conclusion

Cette analyse m’a permis de dégager des insights précieux sur les tendances de ventes et le comportement des clients. Les résultats montrent que certains segments de clients sont plus rentables et actifs que d’autres, offrant des opportunités de ciblage marketing plus précis. Les disparités dans les performances des catégories de produits suggèrent également des opportunités d’ajustement d’inventaire ou de stratégie de promotion. Ces conclusions serviront de base pour affiner la stratégie de Lapage et améliorer son offre en ligne.

En mettant en œuvre ces recommandations, Lapage pourra non seulement maximiser ses revenus actuels en optimisant ses stratégies marketing et ses offres, mais aussi préparer des actions à long terme pour diversifier et stabiliser ses sources de revenus. L'utilisation de l'analyse prédictive et d'approches 

## Livrables

- **Notebook Jupyter** contenant toutes les analyses.
- **Graphiques et visualisations** des corrélations, de la courbe de Lorenz, de l'évolution des ventes et des segmentations.


