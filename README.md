# Guide du Travail de Fin d'Études (TFE)
**Formation :** Développeur Web Back End — Code `X77`
**Réseau :** IFAPME

---

## 1. Objectif du TFE
Le Travail de Fin d'Études est l'**épreuve intégrée** qui clôture vos deux années de formation (en dehors des examens modulaires). Il vise à démontrer votre capacité à concevoir, développer, sécuriser, déployer et documenter de manière autonome une **application back-end de qualité entreprise**, en mobilisant l'ensemble des compétences techniques, architecturales et de gestion de projet acquises durant le cursus.

---

## 2. Choix, cadrage et périmètre technique
Vous avez la liberté de proposer et de personnaliser votre propre sujet selon vos affinités, votre expérience en stage ou un projet professionnel réaliste.

* **Nature du livrable :** Une **application serveur / back-end complète et sécurisée**, reposant sur la programmation orientée objet (ex. Java / Spring Boot), exposant des services réutilisables via **API (REST/CRUD)** et/ou exécutant des traitements automatisés (**batch**).
* **Exigences techniques clés (Module TFE & spécialisation Back End) :**
  * **Architecture logicielle :** Découpage en couches (3-tiers / MVC), respect des design patterns (injection de dépendances, singleton, repository), gestion des dépendances (Maven/Gradle) et externalisation de la configuration (environnements DTAP).
  * **Persistance des données :** Conception et exploitation d'une base de données relationnelle (MySQL) via framework/JDBC.
  * **Sécurité applicative :** Authentification et autorisation (ex. Spring Security, RBAC), chiffrement des données sensibles (au repos et en transit via HTTPS) et protection contre les failles courantes (OWASP Top 10).
  * **Qualité, tests & déploiement :** Tests unitaires/intégration (JUnit), tests d'API (Postman), gestion de version (Git), packaging d'un livrable exécutable (JAR/WAR ou conteneur Docker) et déploiement.
* **Validation obligatoire :** Votre sujet, votre cahier des charges / scénario de réalisation et vos objectifs doivent impérativement être **présentés et approuvés par le formateur et les membres du jury** lors des séances de lancement.

### Critères pour un sujet pertinent (Niveau Coordination/Encadrement)
1. **Ambitieux mais réaliste :** Calibré pour un développement individuel au 2e semestre de la 2e année.
2. **Orienté Services & Architecture :** Met en valeur la robustesse du modèle de données, la logique métier, la sécurité et l'exposition d'API documentées (ex. Swagger/OpenAPI).
3. **Structuré professionnellement :** S'appuie sur un cahier des charges précis et une méthodologie de gestion de projet rigoureuse.

---

## 3. Coaching et suivi (Module TFE - 16h)
Le TFE s'élabore **individuellement au 2e semestre de la 2e année** (en dehors des heures de cours). Vous bénéficiez d'un coaching de **16 heures** réparti en 3 temps :

1. **Lancement (4h en début d'année) :** Présentation des attendus, des critères d'évaluation, de la méthodologie et validation des sujets.
2. **Suivi intermédiaire (4h, idéalement après le Workshop) :** Point d'avancement individuel et collectif, revue d'architecture et résolution des blocages techniques.
3. **Finalisation (8h en fin d'année) :** Relecture structurelle du mémoire, vérification du livrable/des tests d'API et préparation à la soutenance devant le jury.

> **Vos engagements :** Informer régulièrement votre accompagnateur de l'avancement du code et de la rédaction, participer aux séances d'échanges collectifs et intégrer les retours formulés.

---

## 4. Structure et attentes du dossier écrit
Le mémoire technique doit comporter **environ 30 pages minimum (hors annexes)**.

### Plan attendu
1. **Page de garde & Table des matières**
2. **Introduction :** Contexte du projet (besoin métier / système d'information), problématique, objectifs poursuivis et aperçu des méthodes/technologies retenues.
3. **Gestion de projet & Coordination :**
   * Analyse préalable, définition du périmètre et traduction du cahier des charges.
   * Choix et justification de la méthodologie de gestion de projet (Waterfall, Agile, etc.), planification et calendrier.
   * **Évaluation des coûts** (ressources matérielles, hébergement/serveurs et ressources humaines nécessaires).
   * **Coordination et relations** avec les différents intervenants (analyste, front-end, testeurs), partenaires au projet et fournisseurs.
4. **Conception & Réalisation technique :**
   * **Modélisation & Architecture :** Schémas de base de données (MCD/MLD, normalisation), diagrammes d'architecture logicielle (couches, SOA/REST), choix des interfaces/endpoints et de l'expérience développeur/utilisateur.
   * **Choix technologiques & Sécurité :** Argumentation des frameworks, librairies, stratégie d'authentification/autorisation (RBAC) et protection des données.
   * **Étapes de développement & Déploiement :** De la réception du cahier des charges jusqu'aux tests (unitaires et REST/Postman), débogage, build et déploiement.
   * **Analyse transversale obligatoire :** Explication détaillée des 5 dimensions du projet : **technologique, service, sécurité, maintenance et écologique**.
5. **Conclusion :** Bilan réflexif et auto-évaluation critique (adéquation entre les objectifs initiaux, la méthode appliquée et le résultat obtenu ; difficultés rencontrées et solutions apportées).
6. **Références bibliographiques / Webographie & Annexes** (schémas UML/BDD, documentation des endpoints API, extraits de code commentés, etc.).

---

## 5. Échéances et déroulement de l'épreuve
* **Dépôt du dossier écrit :** À remettre au secrétariat de la section **au plus tard 1 mois avant la présentation orale**.
* **Soutenance devant le jury (30 minutes au total) :**
  * **15 minutes** de présentation synthétique (démonstration technique de l'application/API et focus sur des points d'architecture ou de sécurité précis).
  * **15 minutes** d'échange et de questions-réponses avec le jury (formateurs experts + jury externe).

---

## 6. Grille d'évaluation (Total : 400 points)

Votre travail est évalué sur **400 points** répartis en 4 critères (les critères 1 et 2 sont évalués sur le dossier écrit avant l'oral ; les critères 3 et 4 lors de la soutenance) :

| Critère | Moment d'évaluation | Points | Ce que le jury vérifie |
| :--- | :--- | :---: | :--- |
| **1. Qualité formelle du dossier** | Avant l'oral | **/ 80** | Présence de tous les éléments demandés et concision (30 pts) ; cohérence entre objectifs définis et résultat obtenu (30 pts) ; mise en page claire et attractive (20 pts). |
| **2. Qualité du contenu** | Avant l'oral | **/ 120** | Appropriation et personnalisation du projet (30 pts) ; traitement du périmètre avec rigueur et professionnalisme (30 pts) ; capacité de concrétisation (30 pts) ; pertinence des choix méthodologiques et techniques (30 pts). |
| **3. Maîtrise de la mise en œuvre** | Pendant l'oral | **/ 80** | Qualité du livrable : architecture, sécurité et fonctionnement (30 pts) ; maîtrise des différentes étapes de réalisation jusqu'au déploiement (30 pts) ; prise en compte de la déontologie et de l'éthique (ex. RGPD, protection des données sensibles, licences) (20 pts). |
| **4. Qualité de la présentation orale** | Pendant l'oral | **/ 120** | Clarté et esprit de synthèse de la présentation (20 pts) ; pertinence du développement de points technologiques spécifiques (40 pts) ; respect strict du temps de parole de **15 min** (20 pts) ; justesse des réponses aux questions du jury (40 pts). |

---

## Check-list de démarrage rapide
- [ ] Définir une idée d'application back-end réaliste répondant à un besoin métier concret.
- [ ] Formaliser le cahier des charges (modèle de données, endpoints API / batchs, règles de sécurité et rôles utilisateurs).
- [ ] Faire valider le sujet et le scénario lors de la 1re séance de coaching TFE.
- [ ] Initialiser le dépôt Git, structurer le projet (Maven/Spring Boot), documenter les requêtes (Postman/Swagger) et tenir un journal de bord pour la rédaction.
