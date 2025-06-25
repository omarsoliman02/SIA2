# Spécifications fonctionnelles et techniques - ESG Platform

## Introduction
Cette application web permet la gestion, la validation, l'audit et l'export des indicateurs ESG (Environnement, Social, Gouvernance) pour différents utilisateurs et équipes.

## Architecture technique (très synthétique)
- **Frontend** : HTML5, CSS3 (Bootstrap 5, FontAwesome), JavaScript (vanilla, quelques plugins comme DataTables, Chart.js)
- **Aucune logique backend dans ce document**
- **Responsive** : Oui, adapté desktop/mobile
- **Navigation** : Sidebar fixe, navbar supérieure, navigation par modules

---

## Description des vues principales

### 1. Dashboard
- **Rôle** : Vue d'accueil synthétique et analytique.
- **Contenu** :
  - KPIs principaux (nombre d'indicateurs, taux de validation, en attente, récemment modifiés)
  - Graphiques (répartition par catégorie, statut, conformité réglementaire, évolution des données)
  - Tableau de suivi des indicateurs
  - Activité récente
  - Modals pour détails sur indicateurs en attente ou modifiés

### 2. Gestion du dictionnaire
- **Rôle** : Consultation et gestion de la liste des indicateurs ESG.
- **Contenu** :
  - Tableau listant tous les indicateurs (nom, ID, responsable, stockage, type, statut, actions)
  - Filtres par nom, statut, réglementation
  - Actions : modifier, supprimer un indicateur
  - Affichage des détails d'un indicateur (description, unité, source, fréquence, historique, commentaires)

#### 2.1 Ajout d'un indicateur
- **Rôle** : Formulaire pour créer un nouvel indicateur ESG.
- **Contenu** :
  - Champs principaux : nom, ID, catégorie, type, unité, fréquence, description détaillée, stockage, réglementation
  - Validation des champs obligatoires

#### 2.2 Modification d'un indicateur
- **Rôle** : Formulaire pour éditer un indicateur existant.
- **Contenu** :
  - Pré-remplissage des champs
  - Historique des modifications
  - Métadonnées (date création, dernière modif, version, référence, utilisation)

### 3. Validation des indicateurs
- **Rôle** : Suivi et validation des indicateurs par statut (Brouillon, En validation, Validé)
- **Contenu** :
  - Kanban board avec colonnes par statut
  - Cartes d'indicateurs avec description, actions (valider, voir détails)
  - Modal de détails : timeline, commentaires, informations complètes

### 4. Export et intégration
- **Rôle** : Exporter les données ESG et intégrer avec d'autres systèmes.
- **Contenu** :
  - Boutons d'export (CSV, Excel, API, etc.)
  - Liste des exports récents
  - Documentation d'intégration (exemples de code, endpoints)

### 5. Administration & Sécurité
- **Rôle** : Gestion des utilisateurs, des équipes et des paramètres de sécurité.
- **Contenu** :
  - Liste des utilisateurs par équipe, rôles, permissions
  - Actions : ajouter, modifier, supprimer un utilisateur
  - Journal d'activité (connexions, modifications, validations)
  - Paramètres de sécurité (mot de passe, 2FA, SSO, expiration)
  - Statistiques de sécurité (graphiques)

#### 5.1 Ajouter un utilisateur
- **Rôle** : Formulaire pour créer un nouvel utilisateur
- **Contenu** :
  - Champs : prénom, nom, email, équipe, rôle, permissions
  - Validation des champs

### 6. Audit
- **Rôle** : Historique complet des modifications sur les indicateurs
- **Contenu** :
  - Tableau listant toutes les actions (date, indicateur, action, utilisateur, détail)
  - Filtres et recherche

---

## Navigation transversale
- **Sidebar** : Accès rapide à tous les modules
- **Navbar** : Notifications, profil utilisateur, déconnexion
- **Barre utilisateurs connectés** : Affichage en temps réel des utilisateurs actifs

---

## Notes complémentaires
- L'UI est harmonisée sur toutes les pages (couleurs, polices, icônes FontAwesome, responsive)
- Les interactions principales sont accessibles sans rechargement de page (modals, filtres, actions sur tableaux)
- Les données sont fictives ou mockées dans cette version 