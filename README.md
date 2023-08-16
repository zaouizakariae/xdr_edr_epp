# xdr_edr_epp

# Plateforme de protection des points d'extrémité (EPP)

L'objectif de l'EPP est de prévenir les attaques sur les points d'extrémité contre des menaces telles que les logiciels malveillants, les vulnérabilités zero-day et les attaques sans fichier. L'EPP détecte les attaques en utilisant plusieurs méthodes :

- Utilisation de bases de données de signatures connues pour faire correspondre les logiciels malveillants et autres menaces basées sur des fichiers ;
- Blocage ou autorisation d'applications, d'URL, de ports et d'adresses à l'aide de listes noires ou blanches ;
- Fourniture d'un environnement sécurisé pour tester les menaces suspectes, telles que les exécutables ;
- Utilisation d'analystes comportementaux et d'apprentissage automatique pour signaler des activités anormales ou suspectes sur le point d'extrémité.

Les EPP sont déployés sur les points d'extrémité, mais disposent généralement d'une solution basée sur le cloud qui peut collecter les données, les analyser et offrir un accès pratique aux analystes de sécurité.

# Composants de l'EPP
## Éléments clés des solutions EPP
Les solutions EPP sont généralement constituées de plusieurs composants clés, notamment :

- Antivirus et anti-malware : Détecte et supprime les logiciels malveillants connus et les programmes malveillants.
- Firewall : Surveille le trafic réseau et applique des contrôles d'accès pour prévenir les accès non autorisés.
- Système de détection d'intrusion (IDS) : Identifie et signale les éventuelles violations et activités non autorisées.
- Contrôle des appareils : Gère et applique des politiques pour les appareils connectés.
- Prévention de la perte de données (DLP) : Surveille et empêche les données sensibles de quitter le réseau de l'organisation.
## Approche de protection multicouche
L'EPP adopte une approche de protection multicouche, combinant la détection basée sur les signatures, l'analyse comportementale, l'apprentissage automatique et le renseignement sur les menaces pour offrir une couverture de sécurité robuste contre les menaces connues et inconnues.


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
