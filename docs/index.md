# Spotify - Data Governance Framework

## Contexte

Spotify fait face à des volumes de données en forte croissance, à des exigences réglementaires croissantes (GDPR, AI Act, Data Act) et à des risques cyber grandissants. Ce projet propose un cadre de gouvernance des données structuré autour de quatre piliers, appuyé sur un plan de déploiement pilote.

Le cadre s'appuie sur des référentiels reconnus (DMBOK) et vise à garantir la qualité, la sécurité, la conformité et la création de valeur des données à l'échelle de l'entreprise.

## Maturité actuelle

Spotify se situe aujourd'hui entre le niveau **Proactif (niveau 3)** et **Géré (niveau 4)** de maturité en gouvernance des données. Une gouvernance existe aux niveaux global et local, mais les rôles ne sont pas encore formellement définis dans l'ensemble de l'organisation.

## Les quatre piliers

| Pilier | Description | Détails |
|---|---|---|
| **Qualité des données** | Cohérence, exactitude, complétude et disponibilité des données | [→ Qualité des données](pillars/quality.md) |
| **Conformité réglementaire** | Alignement avec le GDPR, le CCPA et les réglementations locales | [→ Conformité réglementaire](pillars/regulatory.md) |
| **Architecture des données** | Intégration, pipelines et élimination des silos | [→ Architecture des données](pillars/architecture.md) |
| **Rôles et responsabilités** | CDO, DPO, Data Stewards et gouvernance organisationnelle | [→ Rôles et responsabilités](pillars/roles.md) |

One additionnal transversal pillar : **data security**: pillars/security.md

## Principaux défis à traiter

| Défi | Impact | Exemple concret | Détaillé dans |
|---|---|---|---|
| Qualité des données | Recommandations sous-optimales, décisions erronées | Métadonnées obsolètes, logs d'activité incomplets | [Qualité des données](pillars/quality.md) |
| Silos de données | Fragmentation, inefficacité, duplication des efforts | Marketing et Produit ont des vues différentes du parcours utilisateur | [Architecture des données](pillars/architecture.md) |
| Accessibilité / Intégration | Retards de développement, faible collaboration | Difficulté à croiser données utilisateur et engagement pour de nouvelles fonctionnalités | [Architecture des données](pillars/architecture.md) |
| Conformité réglementaire internationale | Risques juridiques, amendes, perte de confiance | Conformité GDPR/CCPA, gestion des demandes d'accès utilisateur | [Conformité réglementaire](pillars/regulatory.md) |
| Vie privée des utilisateurs | Perte de confiance, risques juridiques | Transparence sur l'usage des données, gestion du consentement | [Conformité réglementaire](pillars/regulatory.md) |

## Mise en œuvre

Le déploiement du cadre suit une approche progressive : un **plan pilote** est d'abord testé au sein du département Marketing avant un déploiement à l'échelle de l'entreprise.

→ [Consulter le plan pilote](implementation/pilot.md)

## Comité de gouvernance des données

Un **Data Governance Committee**, composé de représentants des rôles clés (CDO en tant que président, Data Stewards, DPO, Head of Engineering — voir [Rôles et responsabilités](pillars/roles.md)), supervise la mise en œuvre du cadre et en garantit la cohérence entre les départements.