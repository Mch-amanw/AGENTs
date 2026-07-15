# Besoin cadré — Plateforme de cadrage de projets assistée par IA

> Projet: 88dc6c1c-d420-4afc-830c-c85229fd12c3
> Session: b1598fd8-83d7-4db8-bcda-b09a7d9d3a86
> Date: 2026-07-15

## Contexte
Le cadrage des projets est aujourd’hui fortement dépendant de l’expérience des chefs de projet et Business Analysts. Les besoins sont recueillis principalement lors de réunions puis retranscrits manuellement dans des documents Word, Excel ou des outils collaboratifs. Cette approche produit des livrables de qualité variable et entraîne des oublis, des incohérences et des retours en arrière pendant les phases de réalisation.

Le projet vise la création d’une plateforme complète de cadrage de projets assistée par des agents IA capables d’accompagner les utilisateurs dans la structuration, la qualification et la formalisation des besoins métier et fonctionnels.

Le MVP cible prioritairement les projets informatiques et de transformation digitale avec une extension possible à d’autres domaines dans les versions futures.

## Problématique
Le processus actuel de cadrage manque d’homogénéité et repose fortement sur les compétences individuelles des intervenants. Les besoins sont parfois incomplets, contradictoires ou mal structurés, ce qui génère des incompréhensions entre équipes métier et techniques, des demandes de clarification répétées et des retards projet.

Les équipes passent également beaucoup de temps à reformuler, consolider et mettre en forme les livrables de cadrage. L’absence de mécanismes systématiques de contrôle de cohérence et de détection des informations manquantes réduit la fiabilité des documents produits.

## Objectifs métier
Le projet vise à standardiser et industrialiser le cadrage des projets afin de produire des besoins plus cohérents, plus complets et plus facilement exploitables.

La plateforme doit réduire significativement le temps nécessaire à la phase de cadrage tout en améliorant la qualité des livrables et la compréhension commune entre équipes métier et techniques.

L’objectif est également d’assister les chefs de projet et Business Analysts sans remplacer leur rôle décisionnel.

## Critères de succès
Le succès du projet sera évalué notamment sur:

- une réduction de 40 à 50 % du temps consacré au cadrage dans les 6 à 12 mois suivant le déploiement;
- une diminution des oublis, ambiguïtés et demandes de clarification pendant les phases de développement;
- une amélioration de l’homogénéité et de la qualité des livrables;
- l’adoption de la plateforme comme outil de référence pour les nouveaux projets;
- une meilleure compréhension des besoins entre parties prenantes métier et techniques.

## Périmètre
Inclus:

- plateforme centralisée de cadrage;
- assistance IA au recueil et à la qualification des besoins;
- génération automatique de livrables de cadrage;
- détection d’informations manquantes, incohérentes ou contradictoires;
- gestion des validations humaines des contenus générés;
- historisation des versions et des validations;
- gestion des risques, hypothèses et dépendances;
- génération des principaux livrables de cadrage du MVP;
- déploiement cloud ou on-premise.

Exclus:

- remplacement des chefs de projet ou Business Analysts;
- génération de spécifications techniques détaillées dans le MVP;
- suivi opérationnel des développements;
- estimation budgétaire avancée et planification détaillée;
- génération de dossiers d’architecture.

## Parties prenantes
Le Product Owner porte la vision du produit et prend les arbitrages de périmètre et de priorisation.

Le comité de pilotage, composé du responsable métier, du chef de projet et du responsable technique, accompagne les décisions structurantes.

Les chefs de projet et Business Analysts constituent les principaux utilisateurs opérationnels.

Les responsables métier et Product Owners expriment et valident les besoins.

Les équipes techniques exploitent les livrables générés pour les phases de conception et de développement.

Les directions pourront consulter des synthèses et indicateurs de cadrage.

## Processus
Processus actuel:

Le cadrage est réalisé au travers de réunions et d’ateliers. Les informations sont ensuite consolidées manuellement dans différents documents sans méthode homogène de contrôle de cohérence. Les besoins sont reformulés et complétés de manière largement artisanale.

Processus cible:

La plateforme accompagne les utilisateurs dans la collecte et la structuration des besoins. Les agents IA posent des questions de clarification, détectent les incohérences, identifient les informations manquantes et proposent des reformulations.

Les livrables de cadrage sont générés automatiquement puis soumis à une validation humaine obligatoire avant diffusion officielle. Les validations, versions et décisions sont historisées afin d’assurer la traçabilité.

## Exigences fonctionnelles
La plateforme devra notamment permettre:

- le recueil structuré des besoins projet;
- l’assistance IA au cadrage;
- la génération automatique de livrables de cadrage;
- la gestion des validations humaines;
- le suivi des versions et modifications;
- la détection d’informations contradictoires ou incomplètes;
- la génération de questions de clarification;
- la priorisation des fonctionnalités;
- la gestion des risques, hypothèses et dépendances;
- la gestion des rôles et droits d’accès.

Le MVP devra générer notamment: expression du besoin, Project Charter, cahier des charges fonctionnel, backlog initial, personas, BPMN simplifié, matrice des parties prenantes, priorisation MoSCoW, risques/hypothèses/dépendances et comptes rendus d’ateliers.

## Exigences non fonctionnelles
La plateforme devra garantir:

- une authentification sécurisée;
- une gestion des rôles et droits;
- le chiffrement des données au repos et en transit;
- la traçabilité des actions utilisateurs et IA;
- la conformité RGPD;
- la possibilité d’un déploiement cloud ou on-premise.

Les objectifs de volumétrie, disponibilité et performance restent à préciser.

## Contraintes
Le MVP doit être disponible dans un délai cible de 4 à 6 mois.

Le projet devra permettre un déploiement progressif après une phase pilote limitée.

La sécurité et la confidentialité des données constituent des contraintes structurantes du projet.

## Dépendances
Le projet dépendra à terme d’intégrations avec Jira, Confluence, Teams, Word, Excel et des solutions de gestion documentaire.

Le mode d’hébergement devra être compatible avec les exigences des organisations clientes.

## Risques
Les données manipulées peuvent contenir des informations sensibles exposées aux modèles IA.

La génération automatique de livrables peut produire des contenus incomplets ou incohérents sans mécanismes de validation adaptés.

Le délai de réalisation du MVP peut imposer une réduction du périmètre fonctionnel initial.

## Planning macro
Le projet prévoit:

- développement du MVP;
- phase pilote avec utilisateurs réels;
- collecte des retours;
- amélioration des fonctionnalités et des agents IA;
- déploiement progressif.

## Livrables
Le projet doit produire une plateforme de cadrage assistée par IA ainsi que les principaux livrables de cadrage métier et fonctionnels générés automatiquement.

## Décisions prises
Le produit sera conçu comme une plateforme complète et non comme un simple assistant intégré.

Les intégrations avec les outils tiers seront traitées dans un second temps.

Le MVP ciblera prioritairement les projets IT et transformation digitale.

Les livrables générés par IA devront être validés par un humain habilité avant diffusion officielle.

## Alternatives écartées
Le positionnement comme simple assistant intégré à des outils tiers a été écarté afin de privilégier une plateforme centralisée couvrant l’ensemble du processus de cadrage.