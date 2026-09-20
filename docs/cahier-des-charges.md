# Cahier des charges – EduGuide BF

## 1. Présentation du projet

### 1.1 Nom du projet

EduGuide BF

### 1.2 Nature du projet

EduGuide BF est une application web d’aide à l’orientation académique et professionnelle destinée principalement aux étudiants et aux élèves du Burkina Faso.

L’application utilisera progressivement des techniques de programmation, d’analyse de données et d’intelligence artificielle afin de proposer des filières et des compétences adaptées au profil de chaque utilisateur.

### 1.3 Porteur du projet

- Nom : Nathan NDJIKI
- Pays : Burkina Faso
- Ville : Ouagadougou
- Domaine : Informatique, intelligence artificielle et applications

### 1.4 État actuel du projet

Le projet est actuellement en phase de cadrage. Cette première version du cahier des charges sert à définir le problème, les utilisateurs, les fonctionnalités et les limites du produit.

---

## 2. Contexte et justification

Le choix d’une filière d’études constitue une décision importante pour les élèves et les étudiants. Pourtant, beaucoup d’entre eux disposent de peu d’informations sur les formations disponibles, les matières exigées, les compétences nécessaires et les débouchés professionnels.

Certains étudiants choisissent une filière en se basant uniquement sur les conseils de leur entourage, sans disposer d’une méthode claire pour comparer les possibilités. D’autres ne connaissent pas les formations correspondant réellement à leurs résultats scolaires, à leurs intérêts ou à leur projet professionnel.

EduGuide BF a pour objectif de proposer un outil simple, accessible et adapté au contexte local pour aider l’utilisateur à mieux comprendre ses possibilités d’orientation.

L’application ne remplacera pas un conseiller d’orientation. Elle fournira plutôt une première aide à la réflexion et encouragera l’utilisateur à rechercher des informations complémentaires auprès des établissements et des professionnels compétents.

---

## 3. Problématique

Comment aider les élèves et les étudiants burkinabè à identifier des filières d’études adaptées à leur niveau, à leurs matières préférées, à leurs compétences et à leur projet professionnel ?

---

## 4. Objectifs du projet

### 4.1 Objectif général

Concevoir une application intelligente d’aide à l’orientation académique qui propose des filières et des recommandations personnalisées à partir du profil de l’utilisateur.

### 4.2 Objectifs spécifiques

L’application devra permettre de :

- recueillir les informations générales sur le profil de l’utilisateur ;
- prendre en compte son niveau d’études ;
- prendre en compte ses résultats dans certaines matières ;
- identifier ses centres d’intérêt ;
- recueillir son projet professionnel ;
- proposer des filières correspondant à son profil ;
- présenter les compétences nécessaires pour chaque filière ;
- identifier les matières ou compétences à renforcer ;
- proposer des ressources d’apprentissage ;
- expliquer les raisons principales de chaque recommandation ;
- permettre à l’utilisateur de comparer plusieurs filières.

---

## 5. Utilisateurs ciblés

### 5.1 Utilisateurs principaux

Les utilisateurs principaux seront :

- les élèves du secondaire ;
- les étudiants en recherche d’orientation ou de réorientation ;
- les étudiants souhaitant poursuivre leurs études dans un domaine spécialisé ;
- les jeunes qui souhaitent mieux comprendre les métiers liés à l’informatique et à l’intelligence artificielle.

### 5.2 Utilisateurs secondaires

Les utilisateurs secondaires pourraient être :

- les conseillers d’orientation ;
- les enseignants ;
- les parents ;
- les établissements d’enseignement ;
- les associations d’accompagnement des jeunes.

### 5.3 Zone de lancement

La première version sera pensée pour les utilisateurs de Ouagadougou et du Burkina Faso.

Une extension à d’autres pays africains francophones pourra être envisagée plus tard.

---

## 6. Périmètre de la première version

La première version, appelée MVP, sera limitée à un nombre réduit de filières afin de rester réalisable.

Les filières initialement étudiées seront :

1. Informatique ;
2. Génie logiciel ;
3. Intelligence artificielle et science des données ;
4. Cybersécurité ;
5. Réseaux et télécommunications ;
6. Systèmes embarqués.

Chaque filière sera décrite avec :

- une présentation générale ;
- les matières importantes ;
- les compétences nécessaires ;
- les qualités personnelles utiles ;
- les débouchés possibles ;
- les formations envisageables ;
- les difficultés ou prérequis à prendre en compte.

---

## 7. Fonctionnalités prévues

### 7.1 Questionnaire utilisateur

L’application posera des questions concernant :

- le niveau d’études ;
- les résultats dans certaines matières ;
- les matières préférées ;
- les domaines d’intérêt ;
- le niveau en informatique ;
- les activités appréciées ;
- le projet professionnel ;
- le type de travail souhaité.

### 7.2 Profil de l’utilisateur

À partir des réponses, l’application construira un profil simplifié de l’utilisateur.

Exemples de caractéristiques :

- intérêt pour les mathématiques ;
- intérêt pour la programmation ;
- intérêt pour les réseaux ;
- intérêt pour la sécurité ;
- intérêt pour l’analyse de données ;
- intérêt pour la création de produits numériques ;
- préférence pour la recherche ou la pratique.

### 7.3 Recommandation de filières

L’application proposera une liste de filières classées selon leur niveau de compatibilité avec le profil de l’utilisateur.

Exemple :

| Filière | Compatibilité | Explication |
|---|---:|---|
| Génie logiciel | 85 % | Bon intérêt pour la programmation et la création d’applications |
| Intelligence artificielle | 78 % | Intérêt élevé pour les mathématiques et l’analyse |
| Cybersécurité | 62 % | Intérêt pour l’informatique, mais connaissances en réseaux à renforcer |

Les pourcentages seront des indications produites par l’application et ne constitueront pas une décision définitive.

### 7.4 Explication des recommandations

Pour chaque filière proposée, l’application devra expliquer :

- les éléments du profil pris en compte ;
- les points forts de l’utilisateur ;
- les compétences à améliorer ;
- les raisons pour lesquelles la filière semble adaptée.

### 7.5 Ressources d’apprentissage

L’application pourra proposer des ressources sur :

- Python ;
- algorithmique ;
- mathématiques ;
- statistiques ;
- bases de données ;
- réseaux ;
- cybersécurité ;
- intelligence artificielle ;
- anglais technique.

Les ressources pourront être ajoutées progressivement dans une base de données.

### 7.6 Comparaison des filières

L’utilisateur pourra comparer plusieurs filières selon :

- les matières principales ;
- les compétences demandées ;
- les types de métiers ;
- la durée des études ;
- les possibilités de spécialisation ;
- les difficultés principales.

---

## 8. Fonctionnement de la recommandation

### 8.1 Première approche

Dans la première version, les recommandations seront basées sur un système de points.

Exemple :

- intérêt pour la programmation : points pour le génie logiciel ;
- intérêt pour les mathématiques : points pour l’intelligence artificielle ;
- intérêt pour les réseaux : points pour les réseaux et télécommunications ;
- intérêt pour la sécurité : points pour la cybersécurité ;
- intérêt pour l’électronique : points pour les systèmes embarqués.

Cette méthode permettra de construire rapidement une première version fonctionnelle et compréhensible.

### 8.2 Évolution vers l’intelligence artificielle

Dans une version ultérieure, un modèle d’apprentissage automatique pourra être utilisé pour :

- classer les profils ;
- prédire les filières les plus adaptées ;
- améliorer les recommandations à partir des retours des utilisateurs ;
- détecter les profils similaires ;
- personnaliser les ressources proposées.

L’intelligence artificielle ne sera ajoutée qu’après la création d’une première version fonctionnelle avec des règles clairement définies.

---

## 9. Données nécessaires

Les données nécessaires pourront comprendre :

- les noms des filières ;
- les matières importantes pour chaque filière ;
- les compétences demandées ;
- les intérêts associés aux filières ;
- les métiers liés à chaque filière ;
- les ressources d’apprentissage ;
- les réponses anonymisées des utilisateurs ;
- les retours sur la pertinence des recommandations.

Les données personnelles non nécessaires ne devront pas être collectées.

Les réponses des utilisateurs devront être anonymisées lorsqu’elles seront utilisées pour améliorer le système.

---

## 10. Contraintes et limites

EduGuide BF devra respecter les limites suivantes :

- l’application ne donnera pas une décision définitive d’orientation ;
- les recommandations ne garantiront pas la réussite dans une filière ;
- les informations sur les formations devront être vérifiées régulièrement ;
- les données personnelles devront être protégées ;
- la première version sera limitée à quelques filières ;
- la qualité des recommandations dépendra de la qualité des données ;
- l’application ne remplacera pas un conseiller d’orientation ;
- les établissements et les conditions d’admission pourront changer.

---

## 11. Technologies envisagées

Les technologies envisagées sont :

- Python pour la programmation ;
- Pandas pour la manipulation des données ;
- Scikit-learn pour l’apprentissage automatique ;
- Streamlit pour l’interface web ;
- Git et GitHub pour la gestion du code ;
- éventuellement SQLite ou un fichier CSV pour stocker les données.

Ces choix pourront évoluer selon les besoins du projet et le niveau de maîtrise du développeur.

---

## 12. Première architecture prévue

L’application pourra être organisée de la manière suivante :

```text
eduguide-bf/
├── app.py
├── data/
│   ├── filieres.csv
│   ├── competences.csv
│   └── ressources.csv
├── src/
│   ├── recommandation.py
│   ├── traitement_donnees.py
│   └── evaluation.py
├── notebooks/
├── docs/
│   └── cahier-des-charges.md
├── tests/
├── requirements.txt
└── README.md
```

---

## 13. Résultats attendus

À la fin de la première phase, le projet devra fournir :

- une application web fonctionnelle ;
- un questionnaire d’orientation ;
- une base contenant au moins six filières ;
- un système simple de recommandation ;
- une explication des recommandations ;
- une documentation technique ;
- un dépôt GitHub organisé ;
- une version déployée accessible en ligne ;
- un rapport sur les tests réalisés avec des étudiants.

---

## 14. Critères d’évaluation

Le projet sera évalué selon les critères suivants :

### Fonctionnalité

L’utilisateur peut remplir le questionnaire et recevoir des recommandations.

### Pertinence

Les recommandations sont cohérentes avec les réponses fournies.

### Explicabilité

L’application explique les raisons principales de chaque recommandation.

### Utilisabilité

L’interface est simple à comprendre et à utiliser.

### Qualité technique

Le code est organisé, documenté et versionné sur GitHub.

### Impact

Le projet répond à un problème réel rencontré par des élèves ou étudiants.

### Évolution

Le projet peut être amélioré avec de nouvelles filières, de nouvelles données et des modèles d’intelligence artificielle.

---

## 15. Plan de développement initial

| Phase | Description | Résultat attendu |
|---|---|---|
| Phase 1 | Recherche et entretiens | Compréhension des besoins |
| Phase 2 | Collecte des données | Base initiale des filières |
| Phase 3 | Développement du système de points | Première recommandation |
| Phase 4 | Création de l’interface | Prototype utilisable |
| Phase 5 | Tests utilisateurs | Retours et corrections |
| Phase 6 | Ajout du machine learning | Recommandations améliorées |
| Phase 7 | Documentation et déploiement | Application présentable |

---

## 16. Questions encore ouvertes

Les questions suivantes devront être étudiées :

- Quelles filières sont les plus demandées par les étudiants ?
- Quelles informations les étudiants jugent-ils les plus importantes ?
- Les utilisateurs préfèrent-ils une application web ou mobile ?
- Quelles données peuvent être obtenues de manière fiable ?
- Comment mesurer la pertinence d’une recommandation ?
- Comment éviter de renforcer les préjugés liés à certaines filières ?
- Comment protéger les informations fournies par les utilisateurs ?
- Quelles ressources gratuites peuvent être recommandées ?
- Comment adapter l’outil aux réalités des autres pays africains francophones ?

---

## 17. Évolution future

Les évolutions possibles sont :

- ajout de nouvelles filières ;
- ajout de formations et d’universités ;
- ajout de plusieurs langues ;
- création d’une application mobile ;
- ajout d’un assistant conversationnel ;
- personnalisation des ressources ;
- ajout de données sur les bourses ;
- ajout de données sur les métiers ;
- collaboration avec des établissements d’enseignement ;
- création d’un tableau de bord pour les conseillers d’orientation.

---

## 18. Version du document

- Version : 0.1
- Date : septembre 2026
- Statut : Document initial de cadrage
- Prochaine révision : après les entretiens avec les étudiants
