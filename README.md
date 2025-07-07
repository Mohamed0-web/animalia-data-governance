# 🐾 Gouvernance des données & qualité de l’information – Animalia Québec

Projet réalisé dans le cadre du cours **GIS 811 – Projet d'intégration en intelligence d'affaires**, Université de Sherbrooke .

## Contexte :

Animalia Québec est une bannière regroupant plusieurs animaleries souhaitant centraliser leur gouvernance informationnelle. Les données proviennent de diverses sources, souvent incohérentes ou incomplètes, ce qui nuit à l’implantation d’outils d’intelligence d’affaires (BI).

Le mandat du projet : **évaluer la qualité des données internes et externes**, identifier les problèmes critiques, puis recommander des solutions techniques et organisationnelles pour une future plateforme BI.

---

## Objectifs :

- Évaluer la qualité des données clients, produits et transactions à partir de fichiers internes et franchisés.
- Détecter les erreurs, doublons, valeurs manquantes et anomalies de structure.
- Produire un diagnostic de gouvernance informationnelle et de maturité.
- Proposer une architecture cible et un plan de transformation réaliste.

---

## Méthodologie :

- **Profilage de données** (complet et semi-automatisé)
- Tests de validité, unicité, complétude, cohérence, format, etc.
- Analyse des processus de gestion des données (méta-gouvernance)
- Rédaction d’un plan de mise en œuvre (axes de gouvernance, rôles, budget, séquences)

---

## Résultats et recommandations :

- Faible conformité sur les champs clés (ex. : ID client, email, produit)
- Nombreux doublons entre franchisés et base centrale
- Absence de dictionnaire de données ou standard de format
- Recommandations :
  - Mise en place d’une gouvernance centralisée
  - Création d’un glossaire de données commun
  - Implémentation d’une architecture hybride (fichiers + base relationnelle)
  - Déploiement d’un ETL léger avant outil BI

## Outils utilisés :

- Microsoft Excel (profilage manuel et automatique)
- Power BI (profilage visuel)
- SQL (requêtes de nettoyage et détection d’anomalies)
- Méthodologie SlideDocs (présentation exécutive)




