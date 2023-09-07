# xdr_edr_epp

# Introduction

Depuis l'aube de l'ère informatique, les points d'extrémité sont la voie la plus simple pour les menaces de sécurité qui évoluent rapidement. Bien que les organisations aient fait la transition des simples logiciels antivirus vers des plates-formes de protection complètes des points d'extrémité (EPP) offrant des capacités de sécurité préventive globale pour les points d'extrémité, jusqu'aux solutions de détection et de réponse aux points d'extrémité (EDR) qui complètent les EPP en ajoutant la capacité de répondre activement aux violations de sécurité des points d'extrémité.

Aujourd'hui, toutes ces technologies de sécurité sont éclipsées par un nouveau modèle appelé XDR ou Extended Detection and Response. En effet, les points d'extrémité sont depuis longtemps une cible majeure pour les attaquants. Que ces points d'extrémité se trouvent dans la poche d'un utilisateur, dans le cloud, sur des appareils IoT ou dans la salle serveurs d'une organisation, les données doivent être protégées à la fois à l'intérieur et à l'extérieur du périmètre de sécurité traditionnel.

# Endpoint protection plateform (EPP)

L'objectif de l'EPP est de prévenir les attaques sur les points d'extrémité contre des menaces telles que les logiciels malveillants, les vulnérabilités zero-day et les attaques sans fichier. L'EPP détecte les attaques en utilisant plusieurs méthodes :

- Utilisation de bases de données de signatures connues pour faire correspondre les logiciels malveillants et autres menaces basées sur des fichiers ;
- Blocage ou autorisation d'applications, d'URL, de ports et d'adresses à l'aide de listes noires ou blanches ;
- Fourniture d'un environnement sécurisé pour tester les menaces suspectes, telles que les exécutables ;
- Utilisation d'analystes comportementaux et d'apprentissage automatique pour signaler des activités anormales ou suspectes sur le point d'extrémité.

Les EPP sont déployés sur les points d'extrémité, mais disposent généralement d'une solution basée sur le cloud qui peut collecter les données, les analyser et offrir un accès pratique aux analystes de sécurité.

# Composants de l'EPP
## Éléments clés des solutions EPP

Pourquoi passer à une solution de sécurité epp ?

  1 - Plusieurs bases de données de renseignements sur les menaces.
  
  2 - Chiffrement des données.
  
  3 - Pare-feu.
  
  4 - Protection contre les intrusions.
  
  5 - Prévention de la perte de données (DLP - Data Loss Prevention).
  
- Les EPP (Plateformes de Protection des Points de Terminaison) sont conçus pour les entreprises et offrent une protection à la fois pour les informations et les utilisateurs à un niveau supérieur.

## Threat Intelligence Databases :

- Les EPP (Plateformes de Protection des Points de Terminaison) devraient avoir accès à plusieurs bases de données.
- Les multiples flux de données constituent le meilleur moyen d'assurer l'exhaustivité et l'actualité des informations.
- Les bases de données incluent des indicateurs de compromission (IoC) et d'autres artefacts.
- Recevoir des flux de données provenant de plusieurs bases de données
  - Offre la meilleure chance de détecter les menaces Zero-Day.
  - Crée une complexité supplémentaire.
- Les EPP sont experts dans la gestion de ces ressources.

## Chiffrement des données :

- Le chiffrement des données sur les points de terminaison est crucial dans l'environnement actuel.
- Le chiffrement brouille les données
  - les rendant illisibles
  - protégeant le système d'exploitation contre certains logiciels malveillants.
- Les informations réglementées devraient toujours être chiffrées.
- Chiffrer toutes les informations commerciales sur les appareils mobiles est une pratique recommandée.

## Pare-feu de point de terminaison :

- Protège les dispositifs individuels.
- Filtre le trafic.
- Applique des politiques de securites.
- Empêche le trafic entrant non sollicité.
- S'adapte à la situation du réseau.

## Détection d'intrusion :

- Fonctionne en conjonction avec le pare-feu.
  - Généralement, détecte d'abord le trafic sortant, avant le pare-feu.
- Analyse les flux de trafic inhabituels.
- Identifie les requêtes vers des domaines malveillants connus.
- Bloque le trafic suspect.
- Génère des alertes pour le Centre Opérationnel de Sécurité (SOC).

## Prévention de la perte de données :

- Limite ou verrouille du deplacement des données.
- Prévient, enregistre ou chiffre les activités USB.
- Surveille et contrôle les transferts de fichiers.
- Restreint l'enregistrement de données localement.
- Classe les données en fonction du niveau de restriction.

# Architecture et Flux de travail de l'EPP

- Collecte et Analyse de Données :
  - Les outils EPP collectent et analysent les données des points de terminaison, y compris l'activité des fichiers, les connexions réseau et le comportement du système, afin d'identifier les menaces potentielles.

- Détection et Atténuation des Menaces :
  - Basées sur l'analyse, les plates-formes EPP détectent et classifient les menaces, déclenchant des alertes et initiant des mesures d'atténuation.

- Réponse aux Incidents et Remédiation :
  - En cas de menace confirmée, les outils EPP facilitent la réponse aux incidents en isolant les points de terminaison, en supprimant les logiciels malveillants et en restaurant les systèmes affectés.

# Cas d'utilisation et Scénarios
## Prévention et détection des logiciels malveillants
L'EPP prévient efficacement les infections par les logiciels malveillants et détecte les fichiers ou activités malveillantes sur les points de terminaison.

## Atténuation des menaces Zero-Day
L'analyse basée sur le comportement et l'apprentissage automatique aident les solutions EPP à détecter et à atténuer les menaces Zero-Day qui ne possèdent pas de signatures connues.

## Surveillance des menaces internes
L'EPP peut aider à identifier les tentatives d'accès non autorisé ou d'exfiltration de données par des initiés.

## Travail à distance sécurisé
Les solutions EPP jouent un rôle crucial dans la sécurisation des points de terminaison utilisés par les travailleurs distants et mobiles, les protégeant ainsi contre les menaces en ligne.



# EDR 

L'EDR fonctionne comme un centre de gestion centralisé pour l'ensemble du réseau d'extrémités d'une organisation. Il agit pour stopper une attaque dès les premiers signes de détection, même avant qu'un administrateur humain ne soit informé de l'existence d'une menace. Alors que l'EPP est une première ligne de défense qui fournit une prévention passive des menaces, l'EDR travaille activement pour atténuer les attaques réseau avant qu'elles ne puissent causer des dommages significatifs.


## Comment fonctionne l'EDR ?

Endpoint Detection and Response (EDR) fonctionne en surveillant en continu et en analysant les activités et les événements sur les points d'extrémité (ordinateurs, serveurs, appareils) au sein d'un réseau afin d'identifier et de réagir aux menaces de sécurité. Voici un aperçu de la manière dont fonctionne l'EDR :

1. Collecte de données : Des agents EDR ou des capteurs sont déployés sur chaque point d'extrémité. Ces agents collectent différents types de données, notamment des journaux système, du trafic réseau, des comportements de fichiers, etc. Les données sont ensuite envoyées vers une plateforme EDR centralisée pour analyse.

2. Analyse des données : La plateforme EDR utilise des algorithmes avancés et l'apprentissage automatique pour analyser les données collectées en temps réel. Elle recherche des comportements inhabituels ou suspects, des indicateurs de compromission (IoC) et des schémas d'attaques connus.

3. Détection des menaces : Lorsque le système EDR identifie une menace potentielle de sécurité, il génère des alertes et des notifications. Ces alertes sont envoyées aux analystes de sécurité ou aux administrateurs, qui peuvent enquêter plus avant.

4. Réponse aux incidents : Les systèmes EDR fournissent des outils pour la réponse aux incidents, y compris la possibilité d'isoler les points d'extrémité compromis, de supprimer les logiciels malveillants et de remédier aux problèmes de sécurité. Certaines solutions EDR peuvent automatiser certaines actions de réponse.

5. Chasse aux menaces : L'EDR permet également aux équipes de sécurité de rechercher de manière proactive des menaces cachées ou avancées qui ne déclenchent pas nécessairement des alertes automatisées. Ce processus s'appelle la chasse aux menaces et implique une enquête manuelle basée sur les données collectées.

6. Enquêtes et analyse : L'EDR conserve un historique des activités des points d'extrémité, ce qui permet aux équipes de sécurité de retracer la source et la chronologie des incidents de sécurité. Cela aide à comprendre comment une menace est entrée dans le réseau et ce qu'elle a fait.

7. Rapports et conformité : Les plateformes EDR offrent souvent des fonctionnalités de reporting et de conformité pour aider les organisations à respecter les exigences réglementaires et à suivre leur posture de sécurité au fil du temps.

8. Surveillance continue : Les solutions EDR proposent une surveillance continue, ce qui signifie qu'elles continuent de rechercher des menaces 24h/24, même lorsque l'environnement du réseau évolue.


## Les Solutions EDR :

Il est important de trouver une solution de sécurité EDR capable de fournir le plus haut niveau de protection tout en demandant le moins d'efforts et d'investissements possibles.

Voici les six aspects clés de l'EDR que vous devriez rechercher :

1. **Visibilité des points d'extrémité :**
Une visibilité en temps réel sur l'ensemble de vos points d'extrémité vous permet de surveiller les activités des adversaires, même lorsqu'ils tentent de pénétrer votre environnement, et de les arrêter immédiatement.

2. **Base de données de menaces :**
Une EDR efficace nécessite d'importantes quantités de télémétrie collectée à partir des points d'extrémité et enrichie en contexte, de manière à pouvoir être analysée à la recherche de signes d'attaques avec diverses techniques d'analyse.

3. **Protection comportementale :**
S'appuyer uniquement sur des méthodes basées sur des signatures ou des indicateurs de compromission (IoC) conduit à un "échec silencieux" qui permet aux violations de données de se produire. Une détection et une réponse aux points d'extrémité efficaces nécessitent des approches comportementales qui recherchent des indicateurs d'attaque (IoA), de sorte que vous soyez alerté des activités suspectes avant qu'une compromission ne puisse se produire.

4. **Compréhension et renseignements :**
Une solution de détection et de réponse aux points d'extrémité qui intègre l'intelligence des menaces peut fournir un contexte, y compris des détails sur l'adversaire attribué qui vous attaque ou d'autres informations sur l'attaque.

5. **Réponse rapide **:
Une EDR qui permet une réponse rapide et précise aux incidents peut stopper une attaque avant qu'elle ne devienne une violation et permettre à votre organisation de reprendre rapidement ses activités.

6. **Solution basée sur le cloud :**
Disposer d'une solution de détection et de réponse aux points d'extrémité basée sur le cloud est le seul moyen d'assurer un impact nul sur les points d'extrémité, tout en veillant à ce que des capacités telles que la recherche, l'analyse et l'investigation puissent être effectuées de manière précise et en temps réel.



# 

Extended Detection and Response (XDR)
XDR est une plateforme intégrée de sécurité et de réponse aux incidents capable de collecter et de corréler automatiquement des données à partir des points d'extrémité ainsi que de nombreuses autres parties de l'environnement informatique. Il s'agit d'une plateforme permettant d'intégrer des données de sécurité issues des outils de gestion des informations et des événements de sécurité (SIEM), de détection et de réponse aux incidents (EDR), d'analyse de réseau et de gestion des identités et des accès (IAM). Elle offre une vue d'ensemble de la cybersécurité de l'ensemble de l'environnement de l'entreprise dans une interface unifiée.

XDR peut standardiser les opérations de sécurité, permettant une analyse cohérente et fiable dans n'importe quel environnement. Il enrichit les sources de données existantes et consolide les informations pour une analyse plus efficace.

L'objectif ultime de la plateforme XDR est d'améliorer la productivité des équipes de sécurité, de permettre des enquêtes plus rapides et plus complètes, et de réduire les temps de réponse aux incidents.

## Comment fonctionne XDR :

XDR connecte les données provenant de solutions de sécurité cloisonnées afin qu'elles puissent travailler ensemble pour améliorer la visibilité des menaces et réduire la durée nécessaire pour identifier et répondre à une attaque. XDR permet des capacités avancées d'investigation forensique et de chasse aux menaces dans plusieurs domaines à partir d'une seule console.

Voici une explication simple étape par étape de comment XDR fonctionne :

**Étape 1. Ingestion :** Ingestion et normalisation de volumes de données à partir d'endpoints, de charges de travail cloud, d'identités, de courriers électroniques, de trafic réseau, de conteneurs virtuels, et bien plus encore.
**Étape 2. Détection :** Analyse et corrélation des données pour détecter automatiquement des menaces furtives à l'aide de l'intelligence artificielle (IA) avancée et de l'apprentissage automatique (ML).
**Étape 3. Réponse :** Priorisation des données de menace en fonction de leur gravité, de sorte que les chasseurs de menaces puissent rapidement analyser et trier les nouveaux événements, et automatiser les activités d'investigation et de réponse.

## Avantages de la sécurité XDR

XDR coordonne et étend la valeur des outils de sécurité cloisonnés, unifiant et rationalisant l'analyse, l'investigation et la remédiation de la sécurité. En conséquence, XDR offre les avantages suivants :

**Visibilité consolidée des menaces :** XDR offre une visibilité granulaire en travaillant sur plusieurs niveaux, collectant et corrélant des données provenant de courriers électroniques, d'endpoints, de serveurs, de charges de travail cloud et de réseaux.

**Détections et investigations sans tracas :** Les analystes et les chasseurs de menaces peuvent se concentrer sur les menaces à haute priorité car XDR élimine les anomalies considérées comme insignifiantes de la chaîne d'alerte. Et avec des analyses avancées et des contenus de corrélation préconstruits dans l'outil, XDR détecte automatiquement les menaces furtives, éliminant ainsi pratiquement le besoin pour les équipes de sécurité de passer leur temps à rédiger, ajuster et gérer constamment des règles de détection.

**Orchestration et réponse de bout en bout : **Le contexte et la télémétrie des menaces détaillés et inter-domaines, allant des hôtes impactés et de la cause première aux indicateurs et aux horaires, guident l'ensemble du processus d'investigation et de remédiation. Les alertes automatisées et les puissantes actions de réponse peuvent déclencher des flux de travail complexes, impliquant plusieurs outils, pour des gains d'efficacité considérables au sein du SOC et une neutralisation ciblée des menaces.

# Quelle est la différence entre EPP et EDR ?
Les solutions EPP agissent comme première ligne de défense contre les attaques visant les points d'extrémité. Les solutions EDR sont conçues pour traiter les menaces que les logiciels EPP ne peuvent pas détecter, aidant à les identifier et à les atténuer après leur occurrence.

Par exemple, des logiciels malveillants zero-day ou d'autres menaces avancées peuvent être détectés par un EPP, mais une fois que le point d'extrémité est attaqué, il commencera à générer une activité inhabituelle. L'EDR peut détecter cette activité, verrouiller automatiquement le point d'extrémité et aider les analystes de sécurité à enquêter plus en profondeur.

                                                              EPP vs EDR

