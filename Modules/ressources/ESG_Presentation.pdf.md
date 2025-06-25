# Présentation de la Plateforme ESG

## Introduction
La plateforme ESG est une application web moderne dédiée à la gestion, la validation, l'audit et l'export des indicateurs ESG (Environnement, Social, Gouvernance). Elle vise à centraliser les données, faciliter la collaboration entre équipes et garantir la traçabilité et la sécurité des informations ESG.

## Objectifs du projet
- Centraliser la gestion des indicateurs ESG
- Faciliter la validation et le suivi par les différentes équipes
- Assurer la traçabilité des modifications et la sécurité des accès
- Offrir une expérience utilisateur moderne, fluide et responsive

## Architecture générale (synthétique)
L'application est développée en HTML5, CSS3 (Bootstrap 5, FontAwesome) et JavaScript. Elle est entièrement responsive et propose une navigation par modules via une sidebar fixe et une navbar supérieure. Les données sont fictives/mockées pour la démonstration.

## Navigation et expérience utilisateur
- **Sidebar** : Accès rapide à tous les modules (Dashboard, Dictionnaire, Validation, Export, Administration, Audit)
- **Navbar** : Notifications, profil utilisateur, déconnexion
- **Barre utilisateurs connectés** : Affichage en temps réel des utilisateurs actifs
- **UI harmonisée** : Couleurs, polices, icônes et responsive design uniformes sur toutes les pages

## Description des vues principales

### Dashboard
Vue d'accueil synthétique et analytique. Elle présente :
- Les KPIs principaux (nombre d'indicateurs, taux de validation, en attente, récemment modifiés)
- Des graphiques analytiques (répartition par catégorie, statut, conformité réglementaire, évolution des données)
- Un tableau de suivi des indicateurs
- L'activité récente
- Des fenêtres modales pour consulter les indicateurs en attente ou récemment modifiés

### Gestion du dictionnaire
Permet de consulter et gérer la liste complète des indicateurs ESG :
- Tableau listant tous les indicateurs (nom, ID, responsable, stockage, type, statut, actions)
- Filtres par nom, statut, réglementation
- Actions : modifier, supprimer un indicateur
- Affichage détaillé d'un indicateur (description, unité, source, fréquence, historique, commentaires)

#### Ajout d'un indicateur
Formulaire dédié à la création d'un nouvel indicateur ESG, avec validation des champs obligatoires.

#### Modification d'un indicateur
Formulaire d'édition avec pré-remplissage, historique des modifications et métadonnées (date de création, dernière modification, version, référence, utilisation).

### Validation des indicateurs
Vue Kanban pour le suivi et la validation des indicateurs :
- Colonnes par statut (Brouillon, En validation, Validé)
- Cartes d'indicateurs avec description, actions (valider, voir détails)
- Modal de détails : timeline, commentaires, informations complètes

### Export et intégration
Permet d'exporter les données ESG et de les intégrer avec d'autres systèmes :
- Boutons d'export (CSV, Excel, API, etc.)
- Liste des exports récents
- Documentation d'intégration (exemples de code, endpoints)

### Administration & Sécurité
Module de gestion des utilisateurs, équipes et paramètres de sécurité :
- Liste des utilisateurs par équipe, rôles, permissions
- Actions : ajouter, modifier, supprimer un utilisateur
- Journal d'activité (connexions, modifications, validations)
- Paramètres de sécurité (mot de passe, 2FA, SSO, expiration)
- Statistiques de sécurité (graphiques)

#### Ajouter un utilisateur
Formulaire pour la création d'un nouvel utilisateur avec validation des champs.

### Audit
Historique complet des modifications sur les indicateurs :
- Tableau listant toutes les actions (date, indicateur, action, utilisateur, détail)
- Filtres et recherche

## Points forts de l'interface
- Navigation fluide et intuitive
- Interface harmonisée et moderne
- Responsive (desktop/mobile)
- Actions principales accessibles sans rechargement de page (modals, filtres, actions sur tableaux)

## Conclusion
La plateforme ESG offre un environnement complet, ergonomique et sécurisé pour la gestion des indicateurs ESG. Elle est conçue pour être facilement prise en main par tous les profils utilisateurs et prête à être connectée à un backend ou à des données réelles. 