# 🏠 Errbmb

Une alternative à Airbnb que l'on ne vous recommande vraiment pas.

Réalisée dans le cadre de l'UE "Architecture Web Avancée" en tant que projet MEAN.

Une version est déployée sur le lien suivant: https://client-h7r9.onrender.com/

## Stack

- Le [backend](https://github.com/Errbmb/backend) est réalisé avec Express et utilise MongoDB.
- Le [frontend](https://github.com/Errbmb/client) est réalisé avec Angular.

![Schema appli](https://github.com/ErrBmb/.github/assets/24733746/f8244e53-f733-43e1-a36c-b7500cf84de9)

Le frontend est responsable d'un affichage simple et élégant, le tout avec une expérience fluide et sans erreurs. Lors d'un
envoi de donnée par le frontend au backend, on procède à la vérification de l'intégrité des données (authentification, respect des
types de données, ...). Une fois cette vérification effectuée, on procède à une/des requête(s) à MongoDB.

### Librairies utilisées

- Mapbox (pour les cartes)
- Zod (pour la vérification des données et la génération des types)
- Express JWT (pour l'authentification)

## Schéma de la base de donnée

TODO

## Étudiants

- [LAVIRON Pablo](https://github.com/0lbap) responsable principalement du développement frontend.
- [VIAL Sébastien](https://github.com/Shyrogan) responsable principalement du développement backend.
