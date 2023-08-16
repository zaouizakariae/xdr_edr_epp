# xdr_edr_epp

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

  1- Plusieurs bases de données de renseignements sur les menaces.
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



#

L'EDR entre en action lorsque qu'un incident de sécurité s'est déjà produit sur un point d'extrémité. Cet outil est utilisé pour examiner et répondre aux menaces et risques. D'autres éléments d'une plateforme EPP sont passifs et servent à prévenir les violations de la sécurité des points d'extrémité. L'EDR est un outil actif qui peut aider à identifier les attaques et à déclencher des solutions automatisées ou des réponses manuelles.

Les outils EDR effectuent généralement les fonctions suivantes :

- aider les analystes à identifier des indicateurs de compromission (IoC), en combinant généralement les données collectées à partir des points d'extrémité avec des renseignements sur les menaces ;
- fournir des alertes en temps réel sur les incidents de sécurité ;
- intégrer des éléments de la médecine légale pour aider les analystes à enquêter sur les points d'extrémité touchés et à identifier la source originale d'une attaque ;
- remédiation automatique, par exemple en isolant, en effaçant ou en réimager un point d'extrémité.

# 

Extended Detection and Response (XDR)
XDR est une plateforme intégrée de sécurité et de réponse aux incidents capable de collecter et de corréler automatiquement des données à partir des points d'extrémité ainsi que de nombreuses autres parties de l'environnement informatique. Il s'agit d'une plateforme permettant d'intégrer des données de sécurité issues des outils de gestion des informations et des événements de sécurité (SIEM), de détection et de réponse aux incidents (EDR), d'analyse de réseau et de gestion des identités et des accès (IAM). Elle offre une vue d'ensemble de la cybersécurité de l'ensemble de l'environnement de l'entreprise dans une interface unifiée.

XDR peut standardiser les opérations de sécurité, permettant une analyse cohérente et fiable dans n'importe quel environnement. Il enrichit les sources de données existantes et consolide les informations pour une analyse plus efficace.

L'objectif ultime de la plateforme XDR est d'améliorer la productivité des équipes de sécurité, de permettre des enquêtes plus rapides et plus complètes, et de réduire les temps de réponse aux incidents.

# Quelle est la différence entre EPP et EDR ?
Les solutions EPP agissent comme première ligne de défense contre les attaques visant les points d'extrémité. Les solutions EDR sont conçues pour traiter les menaces que les logiciels EPP ne peuvent pas détecter, aidant à les identifier et à les atténuer après leur occurrence.

Par exemple, des logiciels malveillants zero-day ou d'autres menaces avancées peuvent être détectés par un EPP, mais une fois que le point d'extrémité est attaqué, il commencera à générer une activité inhabituelle. L'EDR peut détecter cette activité, verrouiller automatiquement le point d'extrémité et aider les analystes de sécurité à enquêter plus en profondeur.
