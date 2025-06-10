# User Journeys - Plateforme ESG

Ce document présente des parcours utilisateurs détaillés (user journeys) pour illustrer l'expérience des différents utilisateurs sur la plateforme ESG d'Ardian.

## Journey 1: Mise en place d'un nouvel indicateur SFDR

### Contexte
Suite à une évolution de la réglementation SFDR, Marie Dupont doit intégrer un nouvel indicateur obligatoire concernant l'empreinte carbone du scope 3 pour les sociétés en portefeuille.

### Étapes détaillées

#### Jour 1: Recherche et préparation
1. Marie reçoit une notification de l'ESMA concernant la mise à jour SFDR
2. Elle consulte la documentation officielle pour comprendre les exigences précises
3. Elle se connecte à la plateforme ESG et analyse les indicateurs existants
4. Elle constate qu'aucun indicateur actuel ne répond exactement à cette exigence
5. Elle prépare un document de travail avec la définition technique de l'indicateur

#### Jour 2: Création de l'indicateur
1. Marie accède au module "Gestion du dictionnaire"
2. Elle clique sur "Ajouter un nouvel indicateur"
3. Elle complète le formulaire avec les informations suivantes:
   - Code: ENV-CO3-01
   - Nom: "Émissions de GES indirectes - Scope 3"
   - Catégorie: Environnement
   - Sous-catégorie: Changement climatique
   - Description: "Mesure les émissions indirectes de gaz à effet de serre du scope 3 selon le GHG Protocol"
   - Méthode de calcul: "Somme des émissions indirectes (en tonnes équivalent CO2) provenant de la chaîne de valeur étendue, incluant les fournisseurs, la logistique, l'utilisation des produits vendus et leur fin de vie"
   - Unité: Tonnes équivalent CO2
   - Fréquence: Annuelle
   - Source de données: "Fournisseurs, données d'activité, facteurs d'émission"
   - Réglementations: SFDR (Article 8)
4. Elle joint le document technique de référence
5. Elle ajoute des tags: #emissions #scope3 #SFDR
6. Elle enregistre l'indicateur avec le statut "Brouillon"

#### Jour 3: Collaboration et révision
1. Marie envoie via la plateforme une demande de révision à:
   - Jean Martin (Expert ESG)
   - Paul Bernard (Finance)
2. Jean reçoit une notification et se connecte à la plateforme
3. Il consulte la définition et ajoute un commentaire: "Préciser les catégories du scope 3 concernées selon la classification du GHG Protocol"
4. Paul suggère d'ajouter une référence aux facteurs d'émission recommandés
5. Marie reçoit ces commentaires et modifie la définition en conséquence
6. Elle répond aux commentaires et les marque comme "Résolus"

#### Jour 4: Validation et finalisation
1. Marie change le statut de l'indicateur en "En validation"
2. Sophie Laurent (administratrice) reçoit une notification pour validation finale
3. Elle vérifie la conformité technique de l'indicateur
4. Elle approuve l'indicateur et change son statut en "Validé"
5. Le système envoie une notification automatique à tous les utilisateurs concernés
6. L'indicateur apparaît désormais dans le dashboard avec un badge "Nouveau"

## Journey 2: Utilisation de la plateforme pour un reporting ESG

### Contexte
Paul Bernard doit préparer un rapport ESG pour un investisseur important qui souhaite une analyse complète des indicateurs environnementaux.

### Étapes détaillées

#### Étape 1: Analyse préliminaire
1. Paul se connecte à la plateforme et accède au Dashboard
2. Il consulte les KPI généraux et remarque que 86% des indicateurs sont validés
3. Il filtre les indicateurs par catégorie "Environnement"
4. Il identifie 30 indicateurs environnementaux validés disponibles

#### Étape 2: Sélection des indicateurs pertinents
1. Paul accède au module "Gestion du dictionnaire"
2. Il utilise la fonction de recherche avancée pour filtrer par:
   - Catégorie: Environnement
   - Statut: Validé
   - Réglementation: SFDR
3. Il sélectionne 15 indicateurs jugés pertinents pour le rapport
4. Il crée une liste personnalisée nommée "Rapport Investisseur Alpha"
5. Il enregistre cette sélection pour usage ultérieur

#### Étape 3: Exploration des données
1. Paul revient au Dashboard et utilise sa liste personnalisée
2. Il examine les tendances et l'évolution des indicateurs sélectionnés
3. Il identifie trois indicateurs montrant des améliorations significatives
4. Il note également deux indicateurs présentant des défis particuliers

#### Étape 4: Exportation et analyse
1. Paul accède au module "Export et Intégration"
2. Il sélectionne sa liste personnalisée "Rapport Investisseur Alpha"
3. Il configure l'export en format Excel avec:
   - Données historiques sur 3 ans
   - Métadonnées complètes (définitions, méthodes de calcul)
   - Graphiques automatiques
4. Il lance l'export et télécharge le fichier
5. Il ouvre le fichier Excel et analyse les données plus en détail

#### Étape 5: Création de visualisations
1. Paul retourne au module "Export et Intégration"
2. Il utilise l'intégration Power BI pour créer un tableau de bord personnalisé
3. Il sélectionne les visualisations les plus pertinentes:
   - Graphique d'évolution des émissions CO2
   - Diagramme de répartition des consommations énergétiques
   - Carte de chaleur des risques climatiques
4. Il partage ce tableau de bord avec l'équipe de direction
5. Il programme un export mensuel automatique

## Journey 3: Onboarding d'un nouveau collaborateur

### Contexte
Sophie Laurent doit intégrer un nouveau collaborateur, Lucas Moreau, qui rejoint l'équipe ESG en tant qu'analyste junior.

### Étapes détaillées

#### Étape 1: Création du profil utilisateur
1. Sophie se connecte à la plateforme et accède au module "Administration et Sécurité"
2. Elle sélectionne "Gestion des utilisateurs" et clique sur "Ajouter un utilisateur"
3. Elle renseigne les informations de Lucas:
   - Nom: Moreau
   - Prénom: Lucas
   - Email: lucas.moreau@ardian.com
   - Département: ESG
   - Poste: Analyste ESG Junior
4. Elle sélectionne le rôle "Contributeur ESG" qui inclut des droits limités

#### Étape 2: Configuration des permissions
1. Sophie accède à l'onglet "Permissions"
2. Elle configure les droits suivants:
   - Consultation: Tous les modules
   - Modification: Dictionnaire (brouillons uniquement)
   - Validation: Aucun droit
   - Export: Données validées uniquement
3. Elle ajoute Lucas au groupe "Équipe ESG"
4. Elle active l'option d'authentification à deux facteurs

#### Étape 3: Personnalisation des notifications
1. Sophie configure les notifications pour Lucas:
   - Nouveaux indicateurs: Notification par email
   - Commentaires: Notification dans l'application
   - Validations: Résumé hebdomadaire
2. Elle désactive les notifications moins pertinentes pour un débutant

#### Étape 4: Génération des accès
1. Sophie clique sur "Générer les identifiants"
2. Le système crée un mot de passe temporaire
3. Sophie programme l'envoi automatique des identifiants pour le jour d'arrivée de Lucas
4. Elle active une période de validité de 24h pour le mot de passe initial

#### Étape 5: Préparation du parcours d'onboarding
1. Sophie accède à la section "Parcours d'intégration"
2. Elle sélectionne le parcours "Nouvel analyste ESG"
3. Elle personnalise les étapes en fonction du profil de Lucas
4. Elle programme l'activation du parcours pour le jour d'arrivée
5. Elle configure des points de contrôle automatiques pour suivre la progression

## Journey 4: Mise à jour d'une méthodologie de calcul

### Contexte
Marie doit mettre à jour la méthodologie de calcul d'un indicateur social suite à une évolution des bonnes pratiques du secteur.

### Étapes détaillées

#### Étape 1: Identification et recherche
1. Marie reçoit une information sur une nouvelle méthodologie recommandée
2. Elle se connecte à la plateforme et accède au "Gestion du dictionnaire"
3. Elle recherche l'indicateur "Taux de fréquence des accidents du travail"
4. Elle consulte la fiche complète de l'indicateur et sa méthodologie actuelle
5. Elle note que la méthodologie date de plus de 2 ans

#### Étape 2: Analyse comparative
1. Marie étudie les différences entre l'ancienne et la nouvelle méthodologie
2. Elle identifie que le principal changement concerne le dénominateur du calcul
3. Elle prépare un document comparatif avec les impacts du changement
4. Elle estime l'impact sur les valeurs historiques (variation d'environ 5-8%)

#### Étape 3: Proposition de modification
1. Marie clique sur "Modifier" dans la fiche de l'indicateur
2. Elle accède à l'historique des versions et crée une nouvelle version
3. Elle met à jour la section "Méthode de calcul" avec la nouvelle formule
4. Elle ajoute une note explicative sur la raison du changement
5. Elle joint son document comparatif en pièce jointe
6. Elle enregistre les modifications avec le statut "En révision"

#### Étape 4: Processus de validation
1. Le système notifie automatiquement les parties prenantes de la modification
2. Jean Martin (expert ESG) examine les changements proposés
3. Il ajoute un commentaire demandant une précision sur l'impact rétrospectif
4. Marie complète l'information demandée et répond au commentaire
5. Jean approuve la modification
6. Sophie (administratrice) vérifie la conformité technique de la mise à jour
7. Elle valide la modification finale

#### Étape 5: Communication et mise en œuvre
1. Le système génère automatiquement une note de changement
2. Marie personnalise cette note avec des explications complémentaires
3. Elle sélectionne les destinataires concernés par ce changement
4. Elle programme une réunion d'information via l'outil de planification intégré
5. Le système archive l'ancienne version tout en la maintenant accessible
6. La nouvelle méthodologie devient la référence officielle
7. Un badge "Méthodologie mise à jour" apparaît sur l'indicateur dans le dashboard

## Journey 5: Gestion d'un audit externe

### Contexte
L'entreprise fait l'objet d'un audit ESG externe et Sophie doit préparer l'accès aux informations pertinentes pour les auditeurs.

### Étapes détaillées

#### Étape 1: Réception de la demande d'audit
1. Sophie reçoit une notification formelle d'audit externe
2. Elle se connecte à la plateforme et accède au module "Administration et Sécurité"
3. Elle crée un nouveau projet d'audit dans la section dédiée
4. Elle enregistre les informations clés:
   - Nom de l'auditeur: EcoVeritas
   - Période d'audit: 15-30 juin 2025
   - Périmètre: Indicateurs environnementaux
   - Niveau d'accès requis: Consultation

#### Étape 2: Configuration des accès temporaires
1. Sophie sélectionne "Créer un profil d'accès temporaire"
2. Elle configure les paramètres:
   - Durée: 15 jours (période d'audit)
   - Modules accessibles: Dictionnaire, Dashboard (lecture seule)
   - Indicateurs visibles: Catégorie Environnement uniquement
   - Historique: 3 dernières années
3. Elle génère trois comptes utilisateurs pour l'équipe d'audit
4. Elle active l'option "Traçabilité renforcée" pour suivre toutes les consultations

#### Étape 3: Préparation de la documentation
1. Sophie accède au module "Export et Intégration"
2. Elle crée un package d'audit personnalisé incluant:
   - Méthodologies complètes des indicateurs
   - Journal des modifications sur 3 ans
   - Rapports de validation
   - Sources de données référencées
3. Elle génère un espace documentaire sécurisé
4. Elle y télécharge les documents complémentaires requis

#### Étape 4: Briefing interne
1. Sophie organise une réunion avec les équipes concernées
2. Elle partage un tableau de bord spécifique "Préparation Audit"
3. Elle assigne des responsabilités pour les différentes parties de l'audit
4. Elle configure des alertes spécifiques pendant la période d'audit

#### Étape 5: Suivi de l'audit
1. Les auditeurs accèdent à la plateforme avec leurs identifiants temporaires
2. Sophie suit leur activité via le tableau de bord d'administration
3. Elle répond aux demandes d'informations complémentaires
4. Elle organise des sessions de Questions/Réponses via l'outil intégré
5. À la fin de l'audit, elle désactive les accès temporaires
6. Elle génère un rapport complet d'activité pour documentation interne 